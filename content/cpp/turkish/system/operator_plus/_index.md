---
title: operator+()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değer ve belirtilen Decimal nesnesi tarafından temsil edilen değerin toplamını temsil eden Decimal sınıfının yeni bir örneğini döndürür.
type: docs
weight: 2185
url: /tr/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) fonksiyon

Belirtilen değer ve belirtilen [Decimal](../decimal/) nesnesi tarafından temsil edilen değerin toplamını temsil eden yeni bir [Decimal](../decimal/) sınıfı örneği döndürür.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const T\& | İlk toplandığı |
| d | const [Decimal](../decimal/)\& | [Decimal](../decimal/) nesnesinin ikinci toplandığı terimi temsil eden sabit referans |

### Dönüş Değeri

[Decimal](../decimal/) sınıfının, **x** ve **d** tarafından temsil edilen değerin toplamını temsil eden yeni bir örneği.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) fonksiyon

Sağ el delegesindeki tüm geri çağrıları sol el delegesinin geri çağrı listesinin sonuna bağlar.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Geri çağrıların ekleneceği delegesi. |
| rhv | MulticastDelegate\<T\> | Geri çağrıları eklenen delegesi. |

### Dönüş Değeri

Sol el değerinin geri çağrılarını ve ardından sağ el değerinin geri çağrılarını içeren bir delegesi döndürür.

## System::operator+(const T1\&, const Nullable\<T2\>\&) fonksiyon

Nullable olmayan ve nullable değerleri toplar.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sol operand tipi. |
| T2 | Sağ operand tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| some | const T1\& | Sol operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Sağ operand. |

### Dönüş Değeri

Toplama sonucu.

## System::operator+(T\&, const String\&) fonksiyon

[String](../string/) birleştirme.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [String](../string/) literal tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | T\& | Dizeye birleştirilecek literal. |
| right | const [String](../string/)\& | [String](../string/) birleştirilecek. |

### Dönüş Değeri

Birleştirilmiş dize.

## System::operator+(T\&, const String\&) fonksiyon

[String](../string/) birleştirme.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [String](../string/) işaretçi tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | T\& | Dizeye birleştirilecek [String](../string/) işaretçi. |
| right | const [String](../string/)\& | [String](../string/) birleştirilecek. |

### Dönüş Değeri

Birleştirilmiş dize.

## System::operator+(const char_t, const String\&) fonksiyon

[String](../string/) birleştirme.

```cpp
String System::operator+(const char_t left, const String &right)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | const char_t | Dizeye birleştirilecek karakter. |
| right | const [String](../string/)\& | [String](../string/) birleştirilecek. |

### Dönüş Değeri

Birleştirilmiş dize.

## Diğer Bağlantılar

* Sınıf [Decimal](../decimal/)
* Sınıf [Nullable](../nullable/)
* Sınıf [String](../string/)
* Yapı [IsStringLiteral](../isstringliteral/)
* Yapı [IsStringPointer](../isstringpointer/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)