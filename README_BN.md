# SDS EDIT — Android প্রজেক্ট (প্রথম প্রোটোটাইপ)

## এই সংস্করণে যা কাজ করে
- Android অ্যাপ হিসেবে চালু হওয়া
- সাদা-নীল SDS EDIT হোম স্ক্রিন
- Android ফাইল পিকার দিয়ে ভিডিও/ছবি/অডিও নির্বাচন
- ভিডিও/ছবি/অডিও প্রিভিউ
- বেসিক timeline তালিকা ও aspect ratio selector

## এখনো তৈরি হয়নি
- প্রকৃত trim/split ও multi-track editing
- MP4 rendering/export
- filters, transitions, keyframes
- AI features
- Premium billing / cloud sync

## APK বানানোর সহজ পথ (মোবাইল থেকেই)
1. GitHub-এ একটি নতুন repository তৈরি করুন (যেমন `sds-edit-android`)।
2. এই ZIP-এর ভেতরের সব ফাইল repository-তে upload করুন।
3. GitHub repository-তে Actions tab খুলুন।
4. `Build SDS EDIT APK` workflow চালান (অথবা main branch-এ push হলে নিজে চলবে)।
5. Workflow সফল হলে Artifacts থেকে `SDS-EDIT-debug-apk` ডাউনলোড করুন।
6. ZIP extract করে `app-debug.apk` Android ফোনে ইনস্টল করুন। Android চাইলে “Install unknown apps” অনুমতি দিন।

## গুরুত্বপূর্ণ
এটি প্রথম কার্যকর Android shell/prototype; CapCut-এর পূর্ণ বিকল্প নয়। APK-টি debug build হবে, Play Store release-এর জন্য পরে signed release build, privacy policy, testing এবং store assets লাগবে।
