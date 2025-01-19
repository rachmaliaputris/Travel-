This Flutter-based travel planning app is designed to streamline the process of trip planning and exploration. It consists of two sides: an admin side for managing places and a user side for planning trips and documenting experiences.

## Features

### Admin Side
- Add new places to the database.
- View a list of all places added.

### User Side
- View all places added by the admin.
- Plan trips by selecting the duration and category (solo, couple, family, friend).
- Countdown timer for trip start date.
- Add a checklist for packing.
- Track expenses such as taxi, food, hotel bills.
- Add blogs and photos related to the trip.
- Favorite places added by the admin.

## Technologies Used

- Firebase: Used for managing the admin side, including authentication and storing place data.
- Shared Preferences: Used for storing user preferences and trip details locally.
- Hive: Used as the local database for storing user data such as checklists and expenses.
- Image Picker: Used for selecting images to upload for trip blogs and photos.
- Lottie Animation: Used for adding animations to enhance the user experience.


### Requirements

- Flutter SDK
- Dart

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/rachmaliaputris/Travel-.git
   cd Travel

2. Install dependencies:
   ```bash
   flutter pub get
3. Run the app:
   ```bash
   flutter run
