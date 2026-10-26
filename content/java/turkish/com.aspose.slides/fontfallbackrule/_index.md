---
title: FontFallBackRule
second_title: Aspose.Slides için Java API Referansı
description: Yazı tipi geri dönüş kuralını temsil eder
type: docs
url: /tr/com.aspose.slides/fontfallbackrule/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Yazı tipi geri dönüş kuralını temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Yeni bir örnek oluşturur. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Yeni bir örnek oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Yeni bir font(ları) FallBack font listesine ekler. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Yeni bir fontları FallBack font listesine ekler. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Sürekli Unicode aralığının ilk indeksini al. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Sürekli Unicode aralığının ilk indeksini al. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Sürekli Unicode aralığının son indeksini al. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Sürekli Unicode aralığının son indeksini al. |
| [getCount()](#getCount--) | Aralık için tanımlı font sayısını al. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki font adını al. |
| [clear()](#clear--) | Listedeki tüm fontları kaldırır. |
| [remove(String fontName)](#remove-java.lang.String-) | Listedeki belirli bir FallBack fontunun ilk oluşumunu kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Listedeki belirtilen indeksteki FallBack fontunu kaldırır. |
| [toArray()](#toArray--) | Bu kural için tüm FallBack fontlarını içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Listede belirtilen aralıktaki tüm FallBack fontlarını içeren bir dizi oluşturur ve döndürür. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Koleksiyondaki belirtilen kuralın indeksini döndürür. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Yeni bir örnek oluşturur.

--------------------

> ```
> // Create new instance of FantFallBackRule with one font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Create new instance of FantFallBackRule with several fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | long | Unicode aralığının başlangıç indeksi |
| endIndex | long | Unicode aralığının bitiş indeksi |
| fontNames | java.lang.String | FallBack için virgülle ayrılmış font adı veya adları |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Yeni bir örnek oluşturur.

--------------------

> ```
> // FantFallBackRule'un iki font ile yeni bir örneğini oluştur
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // FantFallBackRule'un birkaç font ile yeni bir örneğini oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | long | Unicode aralığının başlangıç indeksi |
| endIndex | long | Unicode aralığının bitiş indeksi |
| fontNames | java.lang.String[] | FallBack için virgülle ayrılmış font adı veya adları |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Yeni bir font(ları) FallBack font listesine ekler.

--------------------

> ```
> // FontFallBackRule'un yeni bir örneğini oluştur
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Kurala ikinci fontu ekle 
>  newRule.addFallBackFonts("MS Gothic");
>  //Kurala üçüncü ve dördüncü fontları ekle 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | FallBack için virgülle ayrılmış font adı veya adları |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Yeni bir fontları FallBack font listesine ekler.

--------------------

> ```
> // FontFallBackRule'un yeni bir örneğini oluştur
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Kurala başka üç font ekle 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack için virgülle ayrılmış font adı veya adları |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Sürekli Unicode aralığının ilk indeksini al.

**Döndürür:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Sürekli Unicode aralığının ilk indeksini al.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Sürekli Unicode aralığının son indeksini al.

**Döndürür:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Sürekli Unicode aralığının son indeksini al.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Aralık için tanımlı font sayısını al. Salt okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Belirtilen indeksteki font adını al. Salt okunur [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


Listedeki tüm fontları kaldırır.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Listedeki belirli bir FallBack fontunun ilk oluşumunu kaldırır.

--------------------

> ```
> // Bir kural oluşturur ve bir font listesi içerir.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Listeden Tahoma'yı kaldır.
>  newRule.remove("Tahoma");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Listeden kaldırılacak fontun adı. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Listedeki belirtilen indeksteki FallBack fontunu kaldırır.

--------------------

> ```
> // Bir kural oluşturur ve bir font listesi içerir.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Listeden Tahoma'yı kaldırıyor.
>  newRule.remove(2);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak fontun sıfır tabanlı indeksi. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Bu kural için tüm FallBack fontlarını içeren bir dizi oluşturur ve döndürür.

--------------------

> ```
> // Bir kural oluşturur ve bir font listesi içerir.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tüm font adlarını dizi olarak al.
>  String[] fontNames = newRule.toArray();
> ```


**Döndürür:**
java.lang.String[] - String dizisi
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Listede belirtilen aralıktaki tüm FallBack fontlarını içeren bir dizi oluşturur ve döndürür.

```
// Bir kural oluşturur ve bir font listesi içerir.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Son iki font adını dizi olarak al.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Eklenecek ilk fontun indeksi. |
| count | int | Eklenecek font sayısı. |

**Döndürür:**
java.lang.String[] - String dizisi
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Koleksiyondaki belirtilen kuralın indeksini döndürür.

--------------------

> ```
> // Bir kural oluşturur ve bir font listesi içerir.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma'nın indeksini al.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Bulunacak fontun adı. |

**Döndürür:**
int - Bir fontun indeksi veya listede bulunamazsa -1.