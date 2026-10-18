# TRi9i: application Android (APK) mnin l-site

L-app hiya **nafs l-site** (https://tri9imaroc-ui.github.io/tri9i/) f 9alb app Android.
Hit kat-fte7 l-site mbachara w kat-khdem m3a nafs Supabase, **kolchi synchronisé**: ay tbddil f l-site (GitHub) kayban f l-app f nafs l-wa9t, bla ma t-3awd t-bni l-APK.

## Kifach tsawb l-APK (b blach, mn GitHub)
1. GitHub: **New repository** smmih `tri9i-app` (Public).
2. **Add file > Upload files**: jbed (mn l-folder) `package.json`, `capacitor.config.json`, `.gitignore`, w folderayn `www` w `assets`. **Commit**.
3. **Add file > Create new file**. F l-khana dyal l-smiya kteb **`.github/workflows/android.yml`** (b l-nqat w s-slash), 7ott fiha l-kontnou dyal l-fichier `android.yml`, **Commit**.
4. Dkhol l tab **Actions**. Ila talab ta2kid, fe3el l-workflows. Dghat 3la **Build Android APK**, ba3d **Run workflow**.
5. Tsenna 5 7ta 10 d9ayeq. Mnin ykmml (3alama khadra), iftah l-run w l-te7t f **Artifacts** kayn **tri9i-apk**: t7mmlo (zip), fkkou, w 3ndek `app-debug.apk`.
6. Sift l-APK l t-telifon (WhatsApp, Drive...). Fl-telifon: **Install**, w ila tlb "install unknown apps" fe3elha.

## Mlahadat
- L-URL li f `capacitor.config.json` khassou ykoun l-URL l-7a9i9i dyal l-site dyalek. Ila bddlti smiyat l-repo awla compte GitHub, bddlo.
- L-app kat-tlob **internet**.
- **Zerr l-mikro ("هضر")** ma kaykhdemch f APK (WebView). Kaykhdem f Chrome. Kteb binatna.
- **iPhone**: ma kaynach APK. Khdem Safari > **Share > Add to Home Screen** (l-site kay-t-installa b7al app).
- **Google Play** kay-tlb APK moussajjel (release) b keystore w compte developer (25$ mra wa7da). L-debug APK mchi lih.
