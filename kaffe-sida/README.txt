Kaffe-sida - instruktioner
---------------------------
Innehåll:
- index.html
- hero.jpg
- coffee1.jpg ... coffee9.jpg

Så här laddar du upp till GitHub Pages:
1) Skapa ett nytt repo på GitHub (eller använd befintligt).
2) Ladda upp alla filer (index.html + bilder).
3) Gå till Settings -> Pages och välj Main branch, sedan Save.
4) Vänta en minut och öppna din GitHub Pages-länk.

Använda Formspree för formulär (så det skickas utan mailklient):
- Gå till https://formspree.io och skapa ett konto (gratis plan finns).
- Skapa ett nytt form-endpoint, t.ex. https://formspree.io/f/your-id
- I index.html ändrar du form-taggen:
    <form action="https://formspree.io/f/your-id" method="POST">
- Ta bort enctype="text/plain" och använd POST. Formspree skickar då e-post till dig.

Byta bilder:
- Ersätt hero.jpg och coffeeN.jpg med dina bilder. Behåll filnamnen eller uppdatera <img src=> i index.html.
