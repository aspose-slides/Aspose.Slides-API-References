---
title: FieldType
second_title: Java API Referansı ile Android için Aspose.Slides
description: Bir alan tipini temsil eder.
type: docs
url: /tr/com.aspose.slides/fieldtype/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)
```
public final class FieldType implements IFieldType
```

Bir alan tipini temsil eder. Bu değer, alan kısmına güncellendiğinde hangi metnin ayarlanacağını belirler.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | Initializes a new instance of FieldType class. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getInternalString()](#getInternalString--) | Returns the internal name of this FieldType object. |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | Returns the internal name of this FieldType object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Checks if this field is equal to another. |
| [hashCode()](#hashCode--) | Returns hashcode for this object. |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | Checks if two FieldType objects is equal. |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | Checks if two FieldType objects is inequal. |
| [getSlideNumber()](#getSlideNumber--) | Current slide's number. |
| [getFooter()](#getFooter--) | Slide's footer. |
| [getHeader()](#getHeader--) | Slide's header. |
| [getDateTime()](#getDateTime--) | Current date and time in default date time format for the rendering application. |
| [getDateTime1()](#getDateTime1--) | Current date and time in a first predefined format (MM/DD/YYYY for english). |
| [getDateTime2()](#getDateTime2--) | Current date and time in a second predefined format (Day, Month DD, YYYY for english). |
| [getDateTime3()](#getDateTime3--) | Current date and time in a third predefined format (DD Month YYYY for english). |
| [getDateTime4()](#getDateTime4--) | Current date and time in a fourth predefined format (Month DD, YYYY for english). |
| [getDateTime5()](#getDateTime5--) | Current date and time in a fifth predefined format (DD-Mon-YY for english). |
| [getDateTime6()](#getDateTime6--) | Current date and time in a sixth predefined format (Month YY for english). |
| [getDateTime7()](#getDateTime7--) | Current date and time in a seventh predefined format (Mon-YY for english). |
| [getDateTime8()](#getDateTime8--) | Current date and time in a eighth predefined format (MM/DD/YYYY hh:mm AM/PM for english). |
| [getDateTime9()](#getDateTime9--) | Current date and time in a ninth predefined format (MM/DD/YYYY hh:mm:ss AM/PM for english). |
| [getDateTime10()](#getDateTime10--) | Current date and time in a tenth predefined format (hh:mm for english). |
| [getDateTime11()](#getDateTime11--) | Current date and time in a eleventh predefined format (hh:mm:ss for english). |
| [getDateTime12()](#getDateTime12--) | Current date and time in a twelfth predefined format (hh:mm AM/PM for english). |
| [getDateTime13()](#getDateTime13--) | Current date and time in a thirteenth predefined format (hh:mm:ss AM/PM for english). |
### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

FieldType sınıfının yeni bir örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | java.lang.String |  |
### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

Bu FieldType nesnesinin dahili adını döndürür. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

Bu FieldType nesnesinin dahili adını döndürür. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bu alanın başka bir alanla eşit olup olmadığını denetler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak alan. |

**Döndürür:**
boolean - Alanlar eşitse Doğru.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Bu nesne için hashcode döndürür.

**Döndürür:**
int - Hashcode int.
### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

İki FieldType nesnesinin eşit olup olmadığını denetler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | Karşılaştırılacak ilk FieldType. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | Karşılaştırılacak ikinci FieldType. |

**Döndürür:**
boolean - FieldType nesneleri eşitse Doğru.
### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

İki FieldType nesnesinin eşit olmadığını denetler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | Karşılaştırılacak ilk FieldType. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | Karşılaştırılacak ikinci FieldType. |

**Döndürür:**
boolean - FieldType nesneleri eşit değilse Doğru.
### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

Geçerli slaytın numarası. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

Slaytın altbilgisi. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

Slaytın üstbilgisi. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

Render uygulaması için varsayılan tarih-saat biçiminde mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime1() {#getDateTime1--}
```
public static FieldName getDateTime1()
```

İlk önceden tanımlı biçimde (MM/DD/YYYY İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

İkinci önceden tanımlı biçimde (Day, Month DD, YYYY İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

Üçüncü önceden tanımlı biçimde (DD Month YYYY İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

Dördüncü önceden tanımlı biçimde (Month DD, YYYY İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

Beşinci önceden tanımlı biçimde (DD-Mon-YY İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

Altıncı önceden tanımlı biçimde (Month YY İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

Yedinci önceden tanımlı biçimde (Mon-YY İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

Sekizinci önceden tanımlı biçimde (MM/DD/YYYY hh:mm AM/PM İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

Dokuzuncu önceden tanımlı biçimde (MM/DD/YYYY hh:mm:ss AM/PM İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

Onuncu önceden tanımlı biçimde (hh:mm İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

On birinci önceden tanımlı biçimde (hh:mm:ss İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

On ikinci önceden tanımlı biçimde (hh:mm AM/PM İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

On üçüncü önceden tanımlı biçimde (hh:mm:ss AM/PM İngilizce için) mevcut tarih ve saat. Sadece-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Döndürür:**
[FieldType](../../com.aspose.slides/fieldtype)