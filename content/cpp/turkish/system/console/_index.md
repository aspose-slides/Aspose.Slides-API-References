---
title: Console
second_title: Aspose.Slides için C++ API Referansı
description: Standart çıktı akışına veri yazdırmak için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Hiçbir şekilde örnek oluşturulmamalıdır.
type: docs
weight: 196
url: /tr/system/console/
---
## Console sınıfı

Standart çıktı akışına veri yazdırmak için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Hiçbir şekilde örnek oluşturulmamalıdır.

```cpp
class Console
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| static void [Beep](./beep/)() | UYGULANMADI. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Standart hata akışını temsil eden nesneye işaret eden paylaşımlı bir gösterge döndürür. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Standart giriş akışını temsil eden nesneye işaret eden paylaşımlı bir gösterge döndürür. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Standart çıktı akışını temsil eden nesneye işaret eden paylaşımlı bir gösterge döndürür. |
| static void [Mute](./mute/)(**bool**) | Standart çıktı akışını susturur veya sesini açar. |
| static void [ReadKey](./readkey/)() | UYGULANMADI. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Konsol pencere başlığını ayarlar. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Belirtilen nesneyi sınıfın Error özelliğine atar. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | In özelliğini belirtilen TextReader nesnesine ayarlar. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Belirtilen nesneyi sınıfın Out özelliğine atar. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Belirtilen nesnenin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(**bool**) | bool değerinin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(char_t) | Belirtilen karakter değerini standart çıktı akışına yazdırır. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Belirtilen karakter dizisinin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | [Decimal](../decimal/) değerinin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(**double**) | double hassasiyetli kayan nokta değerinin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(**float**) | float hassasiyetli kayan nokta değerinin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(**int32_t**) | 32-bit tamsayı değerinin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(**int64_t**) | 64-bit tamsayı değerinin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(const [String](../string/)\&) | Belirtilen string nesnesini standart çıktı akışına yazdırır. |
| static void [Write](./write/)(const char_t *) | Belirtilen c-dizgisini standart çıktı akışına yazdırır. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | [TypeInfo](../typeinfo/) değerinin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(**uint32_t**) | unsigned 32-bit tamsayı değerinin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(**uint64_t**) | unsigned 64-bit tamsayı değerinin dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Belirtilen karakter dizisinin belirtilen aralığının dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Belirtilen biçime göre biçimlendirilmiş belirtilen argümanların dize temsili standart çıktı akışına yazdırır. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Mevcut satır sonlandırıcısını standart çıktı akışına yazdırır. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Belirtilen nesnenin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırır. |
| static void [WriteLine](./writeline/)(**bool**) | bool değerinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırır. |
| static void [WriteLine](./writeline/)(char_t) | Belirtilen karakter değeri, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Belirtilen karakter dizisinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | [Decimal](../decimal/) değerinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(**double**) | double hassasiyetli kayan nokta değerinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(**float**) | float hassasiyetli kayan nokta değerinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(**int32_t**) | 32-bit tamsayı değerinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(**int64_t**) | 64-bit tamsayı değerinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Belirtilen string nesnesi, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(const char_t *) | Belirtilen c-dizgesi, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | [TypeInfo](../typeinfo/) değerinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(**uint32_t**) | unsigned 32-bit tamsayı değerinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(**uint64_t**) | unsigned 64-bit tamsayı değerinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Belirtilen karakter dizisinin belirtilen aralığının dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Belirtilen Exception nesnesinin dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Belirtilen biçime göre biçimlendirilmiş belirtilen argümanların dize temsili, ardından mevcut satır sonlandırıcısı eklenerek standart çıktı akışına yazdırılır. |
| static void [WriteLine](./writeline/)(const char *) |  |

## Açıklamalar

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Merhaba mesajını yazdır.
  Console::WriteLine(u"Hello, world!");

  // 'std::array' sınıfının bir örneğini oluştur.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Dizinin elemanlarını yazdır.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Merhaba, dünya!
1 2 3 4 5
*/
```

## İlgili

* İsim Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)