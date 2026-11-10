AFRICA CAR RACING - PROJET ANDROID (prototype)

Ce dossier contient le projet source Android qui embarque le jeu HTML dans une WebView locale.
Le jeu ne demande pas Internet pour démarrer : le fichier du jeu est inclus dans app/src/main/assets/index.html.

IMPORTANT
- Ceci est un projet Android source, pas un APK déjà compilé.
- La compilation nécessite Android SDK/Gradle/JDK 17. Ce projet ne peut pas garantir un fonctionnement parfait sur tous les téléphones sans tests.
- Le prototype de course reste une démo 2D en perspective, pas un jeu 3D natif complet.
- Les publicités, achats Google Play, sauvegardes cloud et multijoueur ne sont pas intégrés.

COMPILATION
1. Ouvrir le projet dans Android Studio.
2. Laisser Gradle synchroniser.
3. Choisir Build > Build Bundle(s) / APK(s) > Build APK(s).
4. L'APK debug sera généré dans app/build/outputs/apk/debug/app-debug.apk.

COMPILATION CLOUD
Le workflow .github/workflows/android.yml peut compiler le projet après dépôt dans un dépôt GitHub.
Dans GitHub : onglet Actions > Build Android APK > Run workflow.
Télécharger ensuite l'artefact AFRICA-CAR-RACING-debug-apk.

Application ID : com.africacarracing.game
Version : 1.0 (prototype)
