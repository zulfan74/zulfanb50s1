README.md
# -- DIV
Div memungkinkan kita untuk mengelompokkan beberapa elemen sebagai satu kesatuan
Fungsi utama: mengelompokkan menjadi container

# -- Sizing:
Width mengatur lebar dari suatu elemen, Height mengatur tinggi dari suatu elemen

Sizing bisa menggunakan pixel, point pica, cm, mm, inches

# -- Penjarakan
Jarak bisa diberikan menggunakan margin dan padding

margin memberikan jarak luar, sehingga dia memiliki jarak antar elemen dengan elemen lainnya

padding memberikan jarak dalam, sehingga dia memiliki jarak antar border dengan elemen di dalamnya

# Git Push (Step By Step)

```bash
git init #inisiasi projek agar di push kedalam repository
git remote add nama_remote https://github.com/username_kalian/repository_kalian.git #untuk menambahkan link remote baru
git add . #untuk menambahkan semua file yang ada dalam folder kedalam commit | NOTE: (.) menandakan bahwa semua file akan ditambahkan
git commit -m "pesan kalian" #untuk memberikan pesan ketika melakukan commit/push kedalam repository
git branch -m main #untuk merubah direksi branch nya dari yang default "master" menjadi "main"
git push origin main #melakukan push terhadap project kedalam repository kita
```
# Git Update (Step By Step)

```bash
git add . #untuk menambahkan semua file yang ada dalam folder kedalam commit | NOTE: (.) menandakan bahwa semua file akan ditambahkan
git commit -m "pesan kalian" #untuk memberikan pesan ketika kita melakukan commit/push kedalam repository
git push origin main #melakukan push terhadap project kedalam repository kita```

Inline Styling > id > class > element

styling menggunakan id akan berbentuk seperti ini:

```css
#div {
    background-color:#000;
}
```

styling menggunakan class akan berbentuk seperti ini :

```css
.div {
    background-color:#000;
}
```

styling menggunakan element akan berbentuk seperti ini:

```css
div {
    background-color:#000;
}
```

align-items mengatur bagian dari vertical
justify-content mengatur bagian dari horizontal


==========================================================

References CDN:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
```

References Link:

{CSS Units} (https://www.w3school.com/css/css_units.asp)

{CSS Table Border} (https://www.w3schools.com/html/html_table_borders.asp)

{Flexbox Cheatsheet} (https://www.yoksel.github.1o/flex-cheatsheet/)

{align-center vs align-items} (https://stackoverflow.com/questions/27539262/whats-the-difference-between-align-content-and-align-items)
