I made this project as part of Aspna to have one place where I can track workouts, nutrition, sleep, weight, and recovery every day.

The main goal is to save daily fitness data and be able to look back at it over time instead of only focusing on one workout or one weigh-in.

What It Tracks
Bodyweight
Calories
Protein
Steps
Sleep hours
Sleep score
Water intake
Energy level
Soreness
Workout completion
Workout type
Daily notes

For workouts, it also tracks:

Exercise
Weight used
Reps
Sets
Training volume
How It Works

When the program starts, the user can choose what they want to do:

1. Daily Check-In
2. Log Workout
3. View Daily History
4. View Workout History
5. Performance Report
6. Exercise Progress
7. Progress Dashboard
8. Exit

A normal daily check-in could look like:

Weight: 123.4 lb
Calories: 1850
Protein: 145g
Steps: 10,450
Sleep: 7.3 hours
Sleep Score: 84
Energy: 8/10
Soreness: 4/10
Workout: Push

For a workout, the user can log something like:

Dumbbell Bench Press
60 lbs
8 reps
3 sets

The program then calculates the training volume:

Volume = Weight × Reps × Sets
Saving Data

I wanted the information to stay saved instead of disappearing every time I closed the program.

The tracker saves the data into Google Drive using two CSV files:

AspnaTracker/
├── daily_data.csv
└── workout_data.csv

One stores daily health and fitness information and the other stores workout data.

Progress Tracking

Once enough data is saved, the program can show things like:

Average bodyweight
Weight change
Average calories
Average protein
Average steps
Average sleep
Average sleep score
Workout consistency
Total training volume

It can also graph bodyweight, sleep, calories, protein, steps, and exercise progress over time.

Built With
Python
Pandas
Matplotlib
Google Drive
Why I Made It

I already track a lot of this information separately, so I wanted to see if I could build something that puts it all together.

This is also one of the smaller projects I am building while working toward the full Aspna platform.

What I Want to Add Next

Some things I want to work on later are:

Weekly reports
Estimated 1 rep max tracking
Strength progress
Workout streaks
Recovery scores
Goal tracking
Plateau detection
Comparing sleep with workout performance
Better dashboards
Web or mobile version

This is still an early version and I plan to keep improving it as I learn more.
