---
title: SizeF
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bazı rastgele bir birimde kayan nokta değerleriyle genişlik ve yükseklik boyutlarını tanımlamak için sınıf.
type: docs
url: /tr/com.aspose.slides.android/sizef/
---
**Kalıtım:**
java.lang.Object
```
public class SizeF
```

Genişlik ve yükseklik boyutlarını bazı rastgele bir birimde kayan nokta değerleriyle tanımlamak için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Yeni bir SizeF örneği oluştur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Boyutun genişliğini al. |
| [getHeight()](#getHeight--) | Boyutun yüksekliğini al. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu boyutun başka bir boyuta eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Boyutu "WxH" formatında bir dize olarak döndür. |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Yeni bir SizeF örneği oluştur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | float | Boyutun genişliği |
| height | float | Boyutun yüksekliği |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Boyutun genişliğini al.

**Döndürür:**
float - genişlik
### getHeight() {#getHeight--}
```
public float getHeight()
```


Boyutun yüksekliğini al.

**Döndürür:**
float - yükseklik
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu boyutun başka bir boyuta eşit olup olmadığını kontrol et.

İki boyut ancak genişlikleri ve yükseklikleri aynı olduğunda eşit kabul edilir.

Bu amaçla, genişlik/yükseklik float değerleri, Float\#floatToIntBits(float).floatToIntBits(float) metodunun her biri uygulandığında aynı int değerini döndürmesi koşulunda aynı kabul edilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Döndürür:**
boolean - true eğer nesneler eşitse, false aksi takdirde
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Döndürür:**
int
### toString() {#toString--}
```
public String toString()
```


Boyutu "WxH" formatında bir dize olarak döndür.

**Döndürür:**
java.lang.String - boyutun dize temsili