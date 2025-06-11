# In your terminal:
git clone https://github.com/<your-username>/Gurrams-ChatApp.git
cd Gurrams-ChatApp

# Copy in your project structure:
# - lib/, android/, assets/, pubspec.yaml, README.md
# - Gurrams-App.apk (the signed APK)
cp -r /path/to/your/source/* .
cp /path/to/Gurrams-App.apk .

# Stage, commit, and push:
git add .
git commit -m "Initial commit: source code + signed APK"
git push origin main
