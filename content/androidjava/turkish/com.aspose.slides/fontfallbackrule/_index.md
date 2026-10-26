---
title: FontFallBackRule
second_title: Aspose.Slides Android için Java API Referansı aracılığıyla
description: Yazı tipi geri dönüş kuralını temsil eder
type: docs
url: /tr/com.aspose.slides/fontfallbackrule/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
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
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Geri dönüş yazı tipi listesine yeni bir yazı tipi ekler. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Geri dönüş yazı tipi listesine yeni yazı tipleri ekler. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Sürekli Unicode aralığının ilk indeksini al. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Sürekli Unicode aralığının ilk indeksini al. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Sürekli Unicode aralığının son indeksini al. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Sürekli Unicode aralığının son indeksini al. |
| [getCount()](#getCount--) | Aralık için tanımlanan yazı tipi sayısını al. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki yazı tipi adını al. |
| [clear()](#clear--) | Listedeki tüm yazı tiplerini kaldır. |
| [remove(String fontName)](#remove-java.lang.String-) | Listedeki belirli bir geri dönüş yazı tipinin ilk oluşumunu kaldır. |
| [removeAt(int index)](#removeAt-int-) | Listedeki belirtilen indeksteki geri dönüş yazı tipini kaldır. |
| [toArray()](#toArray--) | Bu kural için tüm geri dönüş yazı tiplerini içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Listede belirtilen aralıktaki tüm geri dönüş yazı tiplerini içeren bir dizi oluşturur ve döndürür. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Koleksiyondaki belirtilen kuralın indeksini döndürür. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Yeni bir örnek oluşturur.

--------------------

> ```
> // FantFallBackRule sınıfının bir yazı tipiyle yeni bir örnek oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // FantFallBackRule sınıfının birden fazla yazı tipiyle yeni bir örnek oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | long | Unicode aralığının başlangıç indeksi |
| endIndex | long | Unicode aralığının bitiş indeksi |
| fontNames | java.lang.String | FallBack için virgülle ayrılmış bir veya birden fazla yazı tipi adı |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Yeni bir örnek oluşturur.

--------------------

> ```
> // Create new instance of FantFallBackRule with two fonts
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Create new instance of FantFallBackRule with several fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | long | Unicode aralığının başlangıç indeksi |
| endIndex | long | Unicode aralığının bitiş indeksi |
| fontNames | java.lang.String[] | FallBack için virgülle ayrılmış bir veya birden fazla yazı tipi adı |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Geri dönüş yazı tipi listesine yeni bir yazı tipi ekler.

--------------------

> ```
> // FontFallBackRule sınıfının yeni bir örneğini oluştur
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Kurala ikinci bir yazı tipi ekle 
>  newRule.addFallBackFonts("MS Gothic");
>  //Kurala üçüncü ve dördüncü yazı tiplerini ekle 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | FallBack için virgülle ayrılmış bir veya birden fazla yazı tipi adı |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Geri dönüş yazı tipi listesine yeni yazı tipleri ekler.

--------------------

> ```
> //FontFallBackRule sınıfının yeni bir örneğini oluştur
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Kurala başka üç yazı tipi ekle 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack için virgülle ayrılmış bir veya birden fazla yazı tipi adı |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Sürekli Unicode aralığının ilk indeksini al.

**Dönen Değer:**
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

**Dönen Değer:**
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


Aralık için tanımlanan yazı tipi sayısını al. Salt-okunur int.

**Dönen Değer:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Belirtilen indeksteki yazı tipi adını al. Salt-okunur [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönen Değer:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


Listedeki tüm yazı tiplerini kaldır.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Listedeki belirli bir geri dönüş yazı tipinin ilk oluşumunu kaldır.

--------------------

> ```
> // Yazı tiplerinin bir listesini içeren bir kural oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma'yı listeden kaldır.
>  newRule.remove("Tahoma");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Listeden kaldırılacak yazı tipi adı. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Listedeki belirtilen indeksteki geri dönüş yazı tipini kaldır.

--------------------

> ```
> // Yazı tiplerinin bir listesini içeren bir kural oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Minjo, MS Gothic, Tahoma, Times New Roman");
>  //Tahoma'yı listeden kaldırıyor.
>  newRule.remove(2);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak yazı tipinin sıfır tabanlı indeksi. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Bu kural için tüm geri dönüş yazı tiplerini içeren bir dizi oluşturur ve döndürür.

--------------------

> ```
> // Yazı tiplerinin bir listesini içeren bir kural oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tüm yazı tipi adlarını dizi olarak al.
>  String[] fontNames = newRule.toArray();
> ```


**Dönen Değer:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Listede belirtilen aralıktaki tüm geri dönüş yazı tiplerini içeren bir dizi oluşturur ve döndürür.

```
// Yazı tiplerinin bir listesini içeren bir kural oluştur.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Son iki yazı tipi adını dizi olarak al.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Eklenecek ilk yazı tipinin indeksi. |
| count | int | Eklenecek yazı tipi sayısı. |

**Dönen Değer:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Koleksiyondaki belirtilen kuralın indeksini döndürür.

--------------------

> ```
> // Yazı tiplerinin bir listesini içeren bir kural oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma'nın indeksini al.
>  int tahomaIndex = newRule.indexOf("Tahoma");
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Bulunacak yazı tipi adı. |

**Dönen Değer:**
int - Index of a font or -1 if font not found in list.