---
title: ITab
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Metin için bir sekmeyi temsil eder.
type: docs
url: /tr/com.aspose.slides/itab/
---
**Uygulanan Tüm Arayüzler:**
java.lang.Comparable
```
public interface ITab extends Comparable
```

Bir metin için sekme temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPosition()](#getPosition--) | Sekmenin konumunu alır veya ayarlar. |
| [setPosition(double value)](#setPosition-double-) | Sekmenin konumunu alır veya ayarlar. |
| [getAlignment()](#getAlignment--) | Sekmenin hizalama stilini alır veya ayarlar. |
| [setAlignment(int value)](#setAlignment-int-) | Sekmenin hizalama stilini alır veya ayarlar. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Sekmenin konumunu alır veya ayarlar. Bu özelliği atamak, sekmenin koleksiyondaki dizinini değiştirebilir ve Enumerator'ı geçersiz kılabilir. Okunur/Yazılır double.

**Döndürür:**
double
### setPosition(double value) {#setPosition-double-}
```
public abstract void setPosition(double value)
```


Sekmenin konumunu alır veya ayarlar. Bu özelliği atamak, sekmenin koleksiyondaki dizinini değiştirebilir ve Enumerator'ı geçersiz kılabilir. Okunur/Yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Sekmenin hizalama stilini alır veya ayarlar. Okunur/Yazılır [TabAlignment](../../com.aspose.slides/tabalignment).

**Döndürür:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```


Sekmenin hizalama stilini alır veya ayarlar. Okunur/Yazılır [TabAlignment](../../com.aspose.slides/tabalignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |