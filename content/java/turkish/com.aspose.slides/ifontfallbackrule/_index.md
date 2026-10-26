---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: Represents font fallback rule
type: docs
url: /tr/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Yazı tipi geri dönüş kuralını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Listede FallBack yazı tipi(ler) ekler. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Listede FallBack yeni yazı tiplerini ekler. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Sürekli unicode aralığının ilk indeksini al. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Sürekli unicode aralığının son indeksini al. |
| [getCount()](#getCount--) | Aralık için tanımlı olan yazı tipi sayısını al. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki yazı tipi adını al. |
| [clear()](#clear--) | Listeden tüm yazı tiplerini kaldırır. |
| [remove(String fontName)](#remove-java.lang.String-) | Listeden belirli bir FallBack yazı tipinin ilk görünümünü kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Listede belirtilen indeksteki FallBack yazı tipini kaldırır. |
| [toArray()](#toArray--) | Bu kural için tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Listede belirtilen aralıktaki tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Koleksiyondaki belirtilen kuralın indeksini döndürür. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Listede FallBack yeni bir yazı tipi ekler.

--------------------

> ```
> //Yeni bir FantFallBackRule örneği oluştur
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Kurala ikinci bir yazı tipi ekle 
>  newRule.addFallBackFonts("MS Gothic");
>  //Kurala üçüncü ve dördüncü yazı tiplerini ekle 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | FallBack için yazı tipinin adı veya adları (virgülle ayrılmış) |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Listede FallBack yeni yazı tipleri ekler.

--------------------

> ```
> //Yeni bir FontFallBackRule örneği oluştur
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Kurala başka üç yazı tipi ekle 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack için yazı tipinin adı veya adları (virgülle ayrılmış) |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Sürekli unicode aralığının ilk indeksini al.

**Döndürür:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Sürekli unicode aralığının son indeksini al.

**Döndürür:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Aralık için tanımlı olan yazı tipi sayısını al.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Belirtilen indeksteki yazı tipi adını al.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

Listeden tüm yazı tiplerini kaldırır.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Listeden belirli bir FallBack yazı tipinin ilk görünümünü kaldırır.

--------------------

> ```
> // Bir kural oluşturur ve bir yazı tipi listesi içerir.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Listeden Tahoma'yı kaldırma
>  newRule.remove("Tahoma");
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Listeden kaldırılacak yazı tipinin adı. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Listede belirtilen indeksteki FallBack yazı tipini kaldırır.

--------------------

> ```
> // Bir kural oluşturur ve bir yazı tipi listesi içerir.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Listeden Tahoma'yı kaldırma
>  newRule.remove(2);
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak yazı tipinin sıfır tabanlı indeksi. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Bu kural için tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür.

--------------------

> ```
> // Bir kural oluşturur ve bir yazı tipi listesi içerir.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tüm yazı tipi adlarını dizi olarak al
>  String[] fontNames = newRule.toArray();
```

**Döndürür:**
java.lang.String[] - Dize Dizisi
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Listede belirtilen aralıktaki tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür.

--------------------

> ```
> // Bir kural oluşturur ve bir yazı tipi listesi içerir.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Son iki yazı tipi adını dizi olarak al
>  String[] fontNames = newRule.toArray(2,2);
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Eklenecek ilk yazı tipinin indeksi. |
| count | int | Eklenecek yazı tipi sayısı. |

**Döndürür:**
java.lang.String[] - Dize Dizisi
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Koleksiyondaki belirtilen kuralın indeksini döndürür.

--------------------

> ```
> // Bir kural oluşturur ve bir yazı tipi listesi içerir.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Tahoma indeksini al
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Bulunacak yazı tipinin adı. |

**Döndürür:**
int - Yazı tipinin indeksi ya da listede bulunamazsa -1.