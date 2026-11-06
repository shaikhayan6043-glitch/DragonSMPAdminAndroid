DRAGON SMP ADMIN - ANDROID APP PROJECT

यह Android Studio project आपके मौजूदा admin.html को Android ऐप के अंदर खोलता है।
Admin login वही रहेगा जो आपकी वेबसाइट के Supabase Admin Panel में है।

APK बनाने का आसान तरीका (GitHub Actions):
1. GitHub में एक नई खाली repository बनाएं, उदाहरण: DragonSMPAdminAndroid
2. इस ZIP के अंदर की सभी फाइलें और folders उस repository में upload करें।
3. Commit changes करें।
4. GitHub repository में Actions tab खोलें।
5. "Build Dragon SMP Admin APK" workflow पूरा होने दें।
6. सफल run खोलें, नीचे Artifacts में Dragon-SMP-Admin-APK डाउनलोड करें।
7. ZIP खोलकर app-debug.apk फोन में डाउनलोड करें और install करें।

नोट:
- यह debug APK है, Play Store पर publish करने के लिए signed release build चाहिए।
- ऐप admin page खोलता है; यह आपके admin password को source code में save नहीं करता।
- APK तभी सही चलेगा जब आपकी GitHub Pages वेबसाइट पर /admin.html उपलब्ध हो।
- Admin password किसी के साथ share न करें।
