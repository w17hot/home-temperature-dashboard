Home Temperature Dashboard live uploader

This folder contains the Windows uploader that sends the existing Garage_Temperature_Log CSV to the dashboard data branch every 15 minutes.

Use setup-dashboard-upload.ps1 once. It stores the GitHub token encrypted for the current Windows account, remembers the CSV path, performs a test upload, and creates the 15-minute scheduled task.
