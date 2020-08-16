#include <iostream>// tek satırlık yorum satır sonuna kadardır, std::cout için başlık dosyası

/*
  çok satırlı yorum bloğu,  birden fazla satır olabilir.
  programımızın başladığı main fonksiyonumuz.
 */
int main(int argc/*satır için yorum */,char** argv/*argv komut satırı argümanları*/ )
{
    
    std::cout<<"merhaba dunya!";

#if 0
    yaygin olmasada diger bir yorum blogu:
    derleyici önişlemci kontrol yapısında bu şart hiçbir zaman sağlanmayacağı için
    görmezden gelinecek ve burası yorum olacak bizim için
#endif
    
    //TODO(koder_mumin16): IDE'de ayrı bir pencede tüm projenizdeki yorumlari toplu-organize olarak gorebilir, kolayca ilgili satıra ulaşabiliriz 
    
    //TODO(mumin16@hotmail.com): Burda su yapilsin sevgili gelistirme ekibimiz

    //TODO(error 1): Su duzeltilecek
    
}
