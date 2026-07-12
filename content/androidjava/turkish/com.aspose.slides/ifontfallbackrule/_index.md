---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Yazı tipi geri dönüş kuralını temsil eder
type: docs
url: /tr/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Yazı tipi geri dönüş kuralını temsil eder
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Yeni bir yazı tipini(lerini) FallBack yazı tipleri listesine ekler. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Yeni bir yazı tipini(lerini) FallBack yazı tipleri listesine ekler. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Sürekli Unicode aralığının ilk indeksini alır. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Sürekli Unicode aralığının son indeksini alır. |
| [getCount()](#getCount--) | Aralık için gerçekten tanımlanmış yazı tiplerinin sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki yazı tipi adını alır. |
| [clear()](#clear--) | Listedeki tüm yazı tiplerini kaldırır. |
| [remove(String fontName)](#remove-java.lang.String-) | Listedeki belirli bir FallBack yazı tipinin ilk gerçekleşimini kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Listedeki belirtilen indeksteki FallBack yazı tipini kaldırır. |
| [toArray()](#toArray--) | Bu kural için tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Listedeki belirtilen aralıktaki tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Koleksiyondaki belirtilen kuralın indeksini döndürür. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```


Yeni bir yazı tipini(lerini) FallBack yazı tipleri listesine ekler.

--------------------

> ```
> //Yeni bir FantFallBackRule örneği oluştur
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Kurala ikinci bir yazı tipi ekle 
>  newRule.addFallBackFonts("MS Gothic");
>  //Kurala üçüncü ve dördüncü yazı tiplerini ekle 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | FallBack için virgülle ayrılmış yazı tipi adı veya adları |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```


Yeni bir yazı tipini(lerini) FallBack yazı tipleri listesine ekler.

--------------------

> ```
> //Yeni bir FontFallBackRule örneği oluştur
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Kurala başka üç yazı tipi ekle 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack için virgülle ayrılmış yazı tipi adı veya adları |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```


Sürekli Unicode aralığının ilk indeksini alır.

**Döndürür:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```


Sürekli Unicode aralığının son indeksini alır.

**Döndürür:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```


Aralık için gerçekten tanımlanmış yazı tiplerinin sayısını alır.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```


Belirtilen indeksteki yazı tipi adını alır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```


Listedeki tüm yazı tiplerini kaldırır.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```


Listedeki belirli bir FallBack yazı tipinin ilk gerçekleşimini kaldırır.

--------------------

> ```
> // Yazı tiplerinin bir listesini içeren bir kural oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Listeden Tahoma'yı kaldırma
>  newRule.remove("Tahoma");
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Listeden kaldırılacak yazı tipinin adı. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Listedeki belirtilen indeksteki FallBack yazı tipini kaldırır.

--------------------

> ```
> // Yazı tiplerinin bir listesini içeren bir kural oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Listeden Tahoma'yı kaldırma
>  newRule.remove(2);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak yazı tipinin sıfır tabanlı indeksi. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```


Bu kural için tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür.

--------------------

> ```
> // Yazı tiplerinin bir listesini içeren bir kural oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Tüm yazı tipi adlarını dizi olarak al
>  String[] fontNames = newRule.toArray();
> ```


**Döndürür:**
java.lang.String[] - Dizi

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```


Listedeki belirtilen aralıktaki tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür.

--------------------

> ```
> // Yazı tiplerinin bir listesini içeren bir kural oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Son iki yazı tipi adını dizi olarak al
>  String[] fontNames = newRule.toArray(2,2);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| startIndex | int | Eklenecek ilk yazı tipinin indeksi. |
| count | int | Eklenecek yazı tiplerinin sayısı. |

**Döndürür:**
java.lang.String[] - Dizi

### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```


Koleksiyondaki belirtilen kuralın indeksini döndürür.

--------------------

> ```
> //Yazı tiplerinin bir listesini içeren bir kural oluştur.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Tahoma'nın indeksini al
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Bulunacak yazı tipinin adı. |

**Döndürür:**
int - Yazı tipinin indeksi veya bulunamazsa -1.