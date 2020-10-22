# Gunakan Spasi untuk Indentation
Penggunaan karakter tab, sangat bergantung pada operating system dan seringkali tidak portable saat kita coding di mesin yang berbeda-beda. for the sake of portability, ada baiknya gunakan karakter spaces only untuk tab policy.

# Gunakan 4 karakter untuk tab
2 karakter terlalu rapet. 8 karakter kebanyakan.
terlalu rapet bikin sakit mata, kalo kebanyakan... c'mon, this is java dude !

mengutip dari [linux kernel guide](https://www.kernel.org/doc/html/v4.10/process/coding-style.html#indentation) :
>The whole idea behind indentation is to clearly define where a block of control starts and ends. Especially when you’ve been looking at your screen for 20 straight hours, you’ll find it a lot easier to see how the indentation works if you have large indentations.

>Now, some people will claim that having 8-character indentations makes the code move too far to the right, and makes it hard to read on a 80-character terminal screen. The answer to that is that if you need more than 3 levels of indentation, you’re screwed anyway, and should fix your program.

karena di java ada chaining operation (misal : lambda), pemisahan kontrol dan konteks yang jelas jadi sangat penting.

# Pakai 110 Lines width
Berhubung monitor lebar, dan resolusi komputer pun memanjakan mata. untuk saat ini angka 110 sih cukup dapat diterima ya. 

Tapi, jangan salah : prioritas tetap code readibility, patuh terhadap aturan 110 lines width tapi jadi susah dibaca ya buat apa malih.

# Function size (Plis ini penting!!!)
Seperti kata uncle bob, 
>_The first rule of functions is that they should be small._

kedua, 
>_Functions should do something, or answer something, but not both._

Umumnya 1-12 line best, 15 is OK, 20 kebanyakan. 

kalo kebanyakan, ada kemungkinan _function does not do one thing. and absolutely not small._

solusinya cuma 1 : **extract you damn it !!!!**
