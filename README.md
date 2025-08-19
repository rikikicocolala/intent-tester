# Smart Lock Intent Launcher

This repo provides a simple static page that opens the **Google Play Services Smart Lock intent**.

👉 [Intent-tester webpage](https://rikikicocolala.github.io/intent-tester/)


---

## How it works
- GitHub Pages hosts a minimal HTML file.  
- The HTML file contains a link to the following Android intent:  

```text
intent://com.google.android.gms/#Intent;scheme=promote_smartlock_scheme;end
```

- When opened on an Android device, clicking the link (or auto-redirect) should trigger the corresponding intent if supported.  


---

## Notes
- Desktop browsers will usually not recognize `intent://` schemes.  
- The page is designed for Android devices with Google Play Services installed.  
- If the link doesn’t open automatically, tap the link text on the page.  
