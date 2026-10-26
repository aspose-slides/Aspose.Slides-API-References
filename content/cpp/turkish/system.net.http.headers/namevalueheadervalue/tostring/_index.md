---
title: ToString()
second_title: Aspose.Slides for C++ API Referansı
description: C# Object.ToString() metodunun analogu. Özel nesnelerin dizeye dönüştürülmesini sağlar.
type: docs
weight: 79
url: /tr/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const yöntem

C# [Object.ToString()](../../../system/object/tostring/) yönteminin analogu. Özel nesnelerin dizeye dönüştürülmesini sağlar.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### Dönüş Değeri

[String](../../../system/string/) temsili, son sınıf tarafından sağlandığı gibi.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) yöntem

NameValueHeaderValue sınıfı örneklerinin koleksiyonunun dize temsili döndürür.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue sınıfı örneklerinin koleksiyonu. |
| separator | char16_t | Bir dize ayırıcı. |
| leadingSeparator | **bool** | İlk koleksiyon öğesinden önce dize ayırıcı eklenmesi gerektiğini gösteren değer. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Dize temsilinin atanacağı bir örnek. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) yöntem

NameValueHeaderValue sınıfı örneklerinin koleksiyonunun dize temsili döndürür.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue sınıfı örneklerinin koleksiyonu. |
| separator | char16_t | Bir dize ayırıcı. |
| leadingSeparator | **bool** | İlk koleksiyon öğesinden önce dize ayırıcı eklenmesi gerektiğini gösteren değer. |

### Dönüş Değeri

NameValueHeaderValue sınıfı örneklerinin koleksiyonunun dize temsili.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [NameValueHeaderValue](../)
* Sınıf [ObjectCollection](../../objectcollection/)
* Sınıf [StringBuilder](../../../system.text/stringbuilder/)
* AdAlanı [System::Net::Http::Headers](../../)
* Kütüphane [Aspose.Slides](../../../)