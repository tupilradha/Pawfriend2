Paw Track
A community dog care app for Bangalore's street dog volunteers
Bangalore has thousands of street dogs. It also has hundreds of quiet, unglamorous people who feed them, track them, get them vaccinated, and take them to the vet out of their own pockets. They do this every day, on their own roads, largely alone.
This app is built for them.
The Problem
Every volunteer carries the history of their dogs in their head. Which dog is sterilised. Which one bites. Which one hasn't eaten in two days. When they're away — and they do take breaks, fall sick, travel — they hand the round to someone else. A neighbour. A coconut vendor. A friend.
The handoff of responsibility works. The handoff of knowledge doesn't.
The substitute starts from near zero. The volunteer comes back to silence — no record of what happened while they were gone. And if a volunteer stops one day, everything they knew about those dogs stops with them.
What This App Does
It gives each dog a persistent record that outlasts any single person.
A volunteer opens their round each morning and sees every dog — name, photo, last fed, any health flag. They log a feeding in two taps. They record a vet visit with a few lines of notes. When they're travelling, they assign a substitute and that person receives an SMS with a link — no install, no login friction — and sees exactly what they need for the days they're covering. When the volunteer returns, they read everything that happened in their absence in one screen.
The dog's history stays. Even when the person changes.
Who Uses It
Volunteers — the primary users. People who have self-assigned care of 3–4 roads of street dogs in Bangalore. They use the app daily, outdoors, on a phone.
Substitute Caretakers — temporary stand-ins during a volunteer's absence. A vendor, a neighbour, a friend. They may not be tech-savvy. They access the app via an SMS link and must be able to act without any training.
Features — MVP1
Feature
What it does
Dog Profile
Full record for each dog — name, photo, location, physical description, behavioural notes
Daily Feeding Log
Log who fed, when, and any observation
Health Event Log
Record injuries, illnesses, vet visits, vaccinations, sterilisations
Temporary Handoff
Assign a substitute for a date range; they get an SMS and a stripped-down view
My Round
Home screen — all your dogs, last fed, open health flags, at a glance
Return Summary
Everything logged on your dogs while you were away, in one screen
What Is Deliberately Not In MVP1
Maps or GPS
Vet or NGO directory
Expense tracking
Multi-volunteer coordination beyond handoff
Offline mode
These are real needs. They are not V1 needs.
Stack
Layer
Choice
Platform
Mobile browser (no install — share via link or QR code)
Frontend
Optimised for Chrome on Android, Safari on iOS
Backend
Supabase
Auth
OTP via phone number
Notifications
SMS — caretakers receive a link, no app required
Connectivity
MVP1 assumes online
Design Principles
Two taps to any action. If a volunteer has to hunt for something while standing on a road, the design has failed.
Plain language throughout. No jargon, no labels that need explaining.
Rohit must be able to use this. The coconut vendor who steps in for three days is the hardest user to design for. If he can navigate it without help, everyone can.
Kannada / English toggle — preferred, not required for V1.
Scope Discipline
Every feature in this app exists because of a specific real action a real user takes. Before adding anything new, ask: which user does this, when, and what happens if it isn't there? If the answer is unclear, it doesn't belong in this version.
Built for the dogs of Bangalore. And the people who show up for them every day.
