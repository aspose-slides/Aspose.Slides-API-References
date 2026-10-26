---
title: Size
second_title: Aspose.Slides for Android için Java API Referansı
description: Genişlik ve yükseklik boyutlarını bazı keyfi birimde tanımlamak için sınıf.
type: docs
url: /tr/com.aspose.slides.android/size/
---
**Kalıtım:**
java.lang.Object
```
public class Size
```

Genişlik ve yükseklik boyutlarını bazı keyfi birimde tanımlamak için sınıf.
## Constructors

| Yapıcı | Açıklama |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Yeni bir Size örneği oluşturur. |
## Methods

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Boyutun genişliğini alır. |
| [getHeight()](#getHeight--) | Boyutun yüksekliğini alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu boyutun başka bir boyuta eşit olup olmadığını kontrol eder. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Boyutu \"WxH\" biçiminde bir dize olarak döndürür |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

Yeni bir Size örneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | int | Boyutun genişliği |
| height | int | Boyutun yüksekliği |

### getWidth() {#getWidth--}
```
public int getWidth()
```

Boyutun genişliğini alır.

**Returns:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```

Boyutun yüksekliğini alır.

**Returns:**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bu boyutun başka bir boyuta eşit olup olmadığını kontrol eder.

İki boyut yalnızca genişlikleri ve yükseklikleri eşit olduğunda eşittir.

Bir size nesnesi hiçbir zaman başka bir nesne türüne eşit değildir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean - true  if the objects were equal, false otherwise
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```

Boyutu \"WxH\" biçiminde bir dize olarak döndürür.

**Returns:**
java.lang.String - string representation of the size