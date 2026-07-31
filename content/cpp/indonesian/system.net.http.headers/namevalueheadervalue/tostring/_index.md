---
title: ToString()
second_title: Referensi API Aspose.Slides untuk C++
description: Analogi metode C# Object.ToString(). Memungkinkan mengonversi objek khusus menjadi string.
type: docs
weight: 79
url: /id/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const method


Analogi dari metode C# [Object.ToString()](../../../system/object/tostring/). Memungkinkan mengonversi objek khusus ke string.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### Nilai Kembali

[String](../../../system/string/) representasi sebagaimana disediakan oleh kelas final.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) method


Mengembalikan representasi string dari koleksi instance kelas NameValueHeaderValue.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Koleksi instance kelas NameValueHeaderValue. |
| separator | char16_t | Pemisa string. |
| leadingSeparator | **bool** | Nilai yang menunjukkan apakah pemisa string harus ditambahkan sebelum item pertama dalam koleksi. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Sebuah instance di mana representasi string akan diberikan. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) method


Mengembalikan representasi string dari koleksi instance kelas NameValueHeaderValue.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Koleksi instance kelas NameValueHeaderValue. |
| separator | char16_t | Pemisa string. |
| leadingSeparator | **bool** | Nilai yang menunjukkan apakah pemisa string harus ditambahkan sebelum item pertama dalam koleksi. |

### Nilai Kembali

Representasi string dari koleksi instance kelas NameValueHeaderValue.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [NameValueHeaderValue](../)
* Kelas [ObjectCollection](../../objectcollection/)
* Kelas [StringBuilder](../../../system.text/stringbuilder/)
* Ruang Nama [System::Net::Http::Headers](../../)
* Perpustakaan [Aspose.Slides](../../../)