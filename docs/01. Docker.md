# Docker
_Muallif : O'tkirbek Sobirjonov_

**Docker** - bu ochiq kodli platforma bo'lib, yengil ishlaydi, virtual konteynerlarda ilovalarni yaratishni, joylashtirishni va boshqarishni avtomatlashtirishtiradi. Ushbu konteynerlar dasturiy ta'minotni ishga tushirish uchun zarur bo'lgan hamma narsani, jumladan dasturiy ta'minot kodlari, dasturiy ta'minot ishlashi uchun zarur bo'lgan dasturlar, tizim vositalari va kutubxonalarni o'z ichiga oladi va turli muhitlarda barqaror va ishonchli ishlashni ta'minlaydi.

**Docker** linux, mac va windows operatsion tizimlarida yaxshi ishlaydi va sizga o'zingiz hohlagan yadro asosida virtual konteynerlar yaratish imkoniyatini taqdim etadi. Bu orqali siz windows operatsion tizimiga docker o'rnatib, uni ichida bir nechta linux yadrosi asosida ishlovchi operatsion tizimlaridan foydalanishingiz mumkin bo'ladi, agar hohlasangiz windows konteynerlardan ham foydalanishingiz mumkin bo'ladi. Muhimi bitta yadrodan foydalanadigan konteynerlar bo'lishi kerak.

Misol tariqasida: Sizning kompyuteringizga Windows OS o'rnatilgan, siz unga docker o'rnatib, docker ichida Ubuntu, Kali linux, Arch linux, Alpine, Debian, va boshqa istalgan `distribution`laridan foydalanishingiz mumkin. Ushbu virtual konteynerlar ixcham bo'ladi va dasturingizni ishlashi uchun ortiqcha bo'lgan dastur yoki elementlardan holi bo'ladi.

Dockerning yana bir muhim afzalligi shundaki, u operatsion tizim va unga o'rnatilgan boshqa dastur va elementlardan izoliyatsiya qilingan bo'ladi, ya'ni operatsion tizimga o'rnatilgan boshqa dasturlarni qo'shilishi, o'chirilishi, versiyasi ortishi yoki kamayishi docker va uni ichidagi konteynerlarga hech qanday zarar keltirmaydi, chunki konteynerlar o'ziga kerakli hamma narsani doim o'zi bilan olib yuradi. Shuning uchun tashqi aloqalar konteynerga tasir qilmaydi. 

Agar siz docker asosida qurilgan loyihani bir serverdan ikkinchisiga olib o'tmoqchi bo'lsangiz ham osongina olib o'ta olasiz, chunki bir serverdan ikkinchi serverga yoki boshqa vaqtlarda chiqadigan muammolar dockerda chiqmaydi. Docker ichida to'g'ri ishlayotgan dasturiy ta'minot, docker bilan birga istalgan muhitga o'rnatilsa muammosiz ishlayveradi. Agar siz qanday boshqacha xatolar chiqishi haqida habardor bo'lmasangiz keling quyidagi misolga qarab o'taylik: Sizning bir ijtimoiy tarmoq dasturingiz bor va uni serverga `deploy` qilganingizda, dastur bilan bilan birga compiler va runtime larni ham o'rnatishingiz mumkin, yoki boshqa qandaydir dasturlarni o'rtanishingiz talab qilinishi mumkin, ba'zi hollarda aniq versiyada o'rnatishingiz ham talab qilinadi. Chunki sanab o'tilgan dasturlarni serverda yangilasangiz, siz integratsiya qilgan funksiyalar yangi versiyalarda o'zgargan bo'lishi mumkin, va avval ishlab turgan dastur ishlamay qolishiga ham olib kelishi mumkin. 

Xo'sh unda docker konteynerlar ichida nega bunday muammo bo'lmaydi? Docker konteynerlarda bunday muammo bo'lmasligini sababi, ushbu konteynerlar operatsion tizimlarni ham birga olib yuradi, konteyner operatsion tizimi, kompyuter operatsion tizimidan izolyatsiya qilingan bo'ladi. Shuning uchun konteynerlarni tashqi operatsion tizim qiziqtirmaydi, Sizga kerakli visitalarni konteynerga to'g'ri versiyasi o'rnatsangiz yetarli, xatto boshqa konteynerga boshqa versiyalarni o'rnatsangiz ham muammosiz ishlayveradi.



