---
title: IsEmpty()
second_title: Aspose.Slides for C++ API Referansı
description: Dizginin boş olup olmadığını kontrol eder.
type: docs
weight: 14
url: /tr/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) yöntemi

Dizginin boş olup olmadığını kontrol eder.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) boş olup olmadığını kontrol etmek için. |

### Dönüş Değeri

True if string is empty (null-length), false otherwise.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) yöntemi

Koleksiyonun boş olup olmadığını kontrol eder.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Koleksiyon tipi. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Kontrol edilecek koleksiyon. |

### Dönüş Değeri

True if collection has zero element count, false otherwise.

## İlgili

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)