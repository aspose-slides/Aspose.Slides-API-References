---
title: ITabEffectiveData
second_title: Aspose.Slides for Android via Java API Referansı
description: Etkin metinlerin sekme durak özelliklerini içeren değişmez nesne.
type: docs
url: /tr/com.aspose.slides/itabeffectivedata/
---
**Uygulanan Tüm Arayüzler:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Etkin metnin sekme durak özelliklerini içeren değişmez nesne.

--------------------

Bu arayüz [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)'nin bir parçası olarak kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPosition()](#getPosition--) | Sekmenin konumunu döndürür. |
| [getAlignment()](#getAlignment--) | Sekmenin hizalama stilini döndürür. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Sekmenin konumunu döndürür. Bu özelliği atamak, sekmenin koleksiyondaki indeksini değiştirebilir ve Enumerator'ı geçersiz kılabilir. Salt-okunur double.

**Döndürür:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Sekmenin hizalama stilini döndürür. Salt-okunur [TabAlignment](../../com.aspose.slides/tabalignment).

**Döndürür:**
int