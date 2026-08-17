---
title: ITabEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Etkin metinlerin sekme duraklatma özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/itabeffectivedata/
---
**Uygulanan Tüm Arabirimler:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Etkin metnin sekme duraklatma özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arabirim, [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) parçası olarak kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPosition()](#getPosition--) | Bir sekmenin konumunu döndürür. |
| [getAlignment()](#getAlignment--) | Bir sekmenin hizalama stilini döndürür. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

Bir sekmenin konumunu döndürür. Bu özelliğe değer atamak, sekmenin koleksiyondaki indeksini değiştirebilir ve Enumerator'ı geçersiz kılabilir. Yalnızca okuma double.

**Döndürür:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Bir sekmenin hizalama stilini döndürür. Yalnızca okuma [TabAlignment](../../com.aspose.slides/tabalignment).

**Döndürür:**
int