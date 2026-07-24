---
title: Debug
second_title: Aspose.Slides C++ için API Referansı
description: Kayıtlı dinleyicilere hata ayıklama bilgisi göndermeyi sağlayan hata ayıklama metodları koleksiyonu. Tüm çıktı fonksiyonları yalnızca Debug içinde çalışır. Bu, örnek hizmetleri olmayan statik bir türdür. Hiçbir şekilde ondan örnek (instance) oluşturulmamalıdır.
type: docs
weight: 105
url: /tr/system.diagnostics/debug/
---
## Debug yapısı


Kayıtlı dinleyicilere hata ayıklama bilgisi göndermeyi sağlayan hata ayıklama metodları koleksiyonu. Tüm çıktı fonksiyonları yalnızca [Debug](./) içinde çalışır. Bu, örnek hizmetleri olmayan statik bir türdür. Hiçbir şekilde ondan örnek (instance) oluşturulmamalıdır.

```cpp
class Debug
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Koşulu doğrula ve başarısızlıkta bilgi gönder. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Koşulu doğrula ve başarısızlıkta bilgi gönder. |
| static void [Assert](./assert/)(**bool**, const char *) | Koşulu doğrula ve başarısızlıkta bilgi gönder. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Koşulu doğrula ve başarısızlıkta bilgi gönder. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Başarısızlık mesajı gönder. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Statik dinleyiciler listesini alır. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Hata ayıklama arayüzüne mesaj yazdır. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Hata ayıklama arayüzüne mesaj yazdır. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Hata ayıklama arayüzüne dize yazar. |
| static void [Write](./write/)(const char_t *) | Hata ayıklama arayüzüne dize yazar. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Koşul doğruysa hata ayıklama arayüzüne dize yazar. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Hata ayıklama arayüzüne satır yazar. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Hata ayıklama arayüzüne satır yazar. |
| static void [WriteLine](./writeline/)(const char_t *) | Hata ayıklama arayüzüne satır yazar. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Hata ayıklama arayüzüne satır yazar. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Koşul doğruysa hata ayıklama arayüzüne satır yazar. |
## Ayrıca Bakınız

* İsim Uzayı [System::Diagnostics](../)
* Kütüphane [Aspose.Slides](../../)