---
title: Tab
second_title: Aspose.Slides for Android via Java API Referansı
description: Metin için bir sekme temsil eder.
type: docs
url: /tr/com.aspose.slides/tab/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Metin için bir sekme temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Creates new Tab |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Returns or sets position of a tab. |
| [setPosition(double value)](#setPosition-double-) | Returns or sets position of a tab. |
| [getAlignment()](#getAlignment--) | Returns or sets align style of a tab. |
| [setAlignment(int value)](#setAlignment-int-) | Returns or sets align style of a tab. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares the current instance with another object of the same type. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


Yeni Tab oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | double | Tab position. |
| align | int | Align. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versiyon. Yalnızca okunabilir long.

**Döndürür:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```


Returns or sets position of a tab. Assigning this property can change tab's index in collection and invalidate Enumerator. Read/write double.

**Döndürür:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


Returns or sets position of a tab. Assigning this property can change tab's index in collection and invalidate Enumerator. Read/write double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Returns or sets align style of a tab. Read/write [TabAlignment](../../com.aspose.slides/tabalignment).

**Döndürür:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Returns or sets align style of a tab. Read/write [TabAlignment](../../com.aspose.slides/tabalignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Geçerli örneği aynı türdeki başka bir nesneyle karşılaştırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak nesne. |

**Döndürür:**
int - 32 bitlik bir tam sayı ve karşılaştırılan öğelerin göreceli sırasını gösterir. Dönüş değeri şu anlamlara gelir: 

 *  < 0 - Bu örnek objeden küçüktür.
 *  = 0 - Bu örnek objeye eşittir.
 *  > 0 - Bu örnek objeden büyüktür.