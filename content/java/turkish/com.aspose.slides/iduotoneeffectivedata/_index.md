---
title: IDuotoneEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Duotone etkisini temsil eden değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/iduotoneeffectivedata/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Duotone etkisini temsil eden değiştirilemez nesne. Her piksel için, clr1 ve clr2'yi lineer bir interpolasyonla birleştirerek o pikselin yeni rengini belirler.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColor1()](#getColor1--) | Koyu pikseller için hedef renk biçimini döndürür. |
| [getColor2()](#getColor2--) | Açık pikseller için hedef renk biçimini döndürür. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


Koyu pikseller için hedef renk biçimini döndürür. Salt okunur java.awt.Color.

**Döndürür:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


Açık pikseller için hedef renk biçimini döndürür. Salt okunur java.awt.Color.

**Döndürür:**
java.awt.Color