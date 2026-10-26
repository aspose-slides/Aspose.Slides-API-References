---
title: FieldType
second_title: Aspose.Slides for Java API Referansı
description: Bir alan türünü temsil eder.
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

Bir alan türünü temsil eder. Bu değer, alan bölümüne güncellendiğinde hangi metnin ayarlanacağını belirler.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | FieldType sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInternalString()](#getInternalString--) | Bu FieldType nesnesinin dahili adını döndürür. |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | Bu FieldType nesnesinin dahili adını döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu alanın başka bir alanla eşit olup olmadığını kontrol eder. |
| [hashCode()](#hashCode--) | Bu nesne için hash kodunu döndürür. |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | İki FieldType nesnesinin eşit olup olmadığını kontrol eder. |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | İki FieldType nesnesinin eşit olmama durumunu kontrol eder. |
| [getSlideNumber()](#getSlideNumber--) | Geçerli slaytın numarası. |
| [getFooter()](#getFooter--) | Slaytın altbilgisi. |
| [getHeader()](#getHeader--) | Slaytın üstbilgisi. |
| [getDateTime()](#getDateTime--) | Render uygulaması için varsayılan tarih saat biçiminde geçerli tarih ve saat. |
| [getDateTime1()](#getDateTime1--) | İlk önceden tanımlı formatta (İngilizce için MM/DD/YYYY) geçerli tarih ve saat. |
| [getDateTime2()](#getDateTime2--) | İkinci önceden tanımlı formatta (İngilizce için Gün, Ay DD, YYYY) geçerli tarih ve saat. |
| [getDateTime3()](#getDateTime3--) | Üçüncü önceden tanımlı formatta (İngilizce için DD Ay YYYY) geçerli tarih ve saat. |
| [getDateTime4()](#getDateTime4--) | Dördüncü önceden tanımlı formatta (İngilizce için Ay DD, YYYY) geçerli tarih ve saat. |
| [getDateTime5()](#getDateTime5--) | Beşinci önceden tanımlı formatta (İngilizce için DD-Mon-YY) geçerli tarih ve saat. |
| [getDateTime6()](#getDateTime6--) | Altıncı önceden tanımlı formatta (İngilizce için Ay YY) geçerli tarih ve saat. |
| [getDateTime7()](#getDateTime7--) | Yedinci önceden tanımlı formatta (İngilizce için Mon-YY) geçerli tarih ve saat. |
| [getDateTime8()](#getDateTime8--) | Sekizinci önceden tanımlı formatta (İngilizce için MM/DD/YYYY hh:mm AM/PM) geçerli tarih ve saat. |
| [getDateTime9()](#getDateTime9--) | Dokuzuncu önceden tanımlı formatta (İngilizce için MM/DD/YYYY hh:mm:ss AM/PM) geçerli tarih ve saat. |
| [getDateTime10()](#getDateTime10--) | Onuncu önceden tanımlı formatta (İngilizce için hh:mm) geçerli tarih ve saat. |
| [getDateTime11()](#getDateTime11--) | On birinci önceden tanımlı formatta (İngilizce için hh:mm:ss) geçerli tarih ve saat. |
| [getDateTime12()](#getDateTime12--) | On ikinci önceden tanımlı formatta (İngilizce için hh:mm AM/PM) geçerli tarih ve saat. |
| [getDateTime13()](#getDateTime13--) | On üçüncü önceden tanımlı formatta (İngilizce için hh:mm:ss AM/PM) geçerli tarih ve saat. |

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

Bu FieldType nesnesinin dahili adını döndürür. Okuma/yazma String.

**Dönüş Değeri:**
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

Bu FieldType nesnesinin dahili adını döndürür. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bu alanın başka bir alanla eşit olup olmadığını kontrol eder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak alan. |

**Dönüş Değeri:**
boolean - Alanlar eşitse True.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Bu nesne için hash kodunu döndürür.

**Dönüş Değeri:**
int - Hashcode tam sayısı.

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

İki FieldType nesnesinin eşit olup olmadığını kontrol eder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | Karşılaştırılacak ilk FieldType. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | Karşılaştırılacak ikinci FieldType. |

**Dönüş Değeri:**
boolean - FieldType nesneleri eşitse True.

### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

İki FieldType nesnesinin eşit olmama durumunu kontrol eder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | Karşılaştırılacak ilk FieldType. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | Karşılaştırılacak ikinci FieldType. |

**Dönüş Değeri:**
boolean - FieldType nesneleri eşit değilse True.

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

Geçerli slaytın numarası. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

Slaytın altbilgisi. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

Slaytın üstbilgisi. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

Render uygulaması için varsayılan tarih saat biçiminde geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

İlk önceden tanımlı formatta (İngilizce için MM/DD/YYYY) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

İkinci önceden tanımlı formatta (İngilizce için Gün, Ay DD, YYYY) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

Üçüncü önceden tanımlı formatta (İngilizce için DD Ay YYYY) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

Dördüncü önceden tanımlı formatta (İngilizce için Ay DD, YYYY) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

Beşinci önceden tanımlı formatta (İngilizce için DD-Mon-YY) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

Altıncı önceden tanımlı formatta (İngilizce için Ay YY) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

Yedinci önceden tanımlı formatta (İngilizce için Mon-YY) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

Sekizinci önceden tanımlı formatta (İngilizce için MM/DD/YYYY hh:mm AM/PM) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

Dokuzuncu önceden tanımlı formatta (İngilizce için MM/DD/YYYY hh:mm:ss AM/PM) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

Onuncu önceden tanımlı formatta (İngilizce için hh:mm) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

On birinci önceden tanımlı formatta (İngilizce için hh:mm:ss) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

On ikinci önceden tanımlı formatta (İngilizce için hh:mm AM/PM) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

On üçüncü önceden tanımlı formatta (İngilizce için hh:mm:ss AM/PM) geçerli tarih ve saat. Yalnızca-okunur [FieldType](../../com.aspose.slides/fieldtype).

**Dönüş Değeri:**
[FieldType](../../com.aspose.slides/fieldtype)