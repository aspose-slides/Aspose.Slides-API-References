---
title: TextAnimation
second_title: Aspose.Slides dla Java – Referencja API
description: Reprezentuje animację tekstu.
type: docs
url: /pl/com.aspose.slides/textanimation/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Reprezentuje animację tekstu.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Dodaje nowy efekt na koniec bieżącej sekwencji do końca grupowych animacji tekstu. |
| [getBuildType()](#getBuildType--) | Lista typu budowania (np. |
| [setBuildType(int value)](#setBuildType-int-) | Lista typu budowania (np. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Powiązany efekt kształtu z grupą lub bez (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Powiązany efekt kształtu z grupą lub bez (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

Dodaje nowy efekt na koniec bieżącej sekwencji do końca grupowych animacji tekstu. Ważny tylko wtedy, gdy liczba akapitów tekstu jest równa lub większa niż liczba efektów w tej grupie!

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| effectType | int | Typ efektu animacji [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy efektu animacji [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ wyzwalacza efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Zwraca:**
[IEffect](../../com.aspose.slides/ieffect) - Nowy obiekt efektu [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

Lista typu budowania (np. akapit 1,2,3, Wszystko naraz) animacji tekstu. Odczyt/zapis [BuildType](../../com.aspose.slides/buildtype).

**Zwraca:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

Lista typu budowania (np. akapit 1,2,3, Wszystko naraz) animacji tekstu. Odczyt/zapis [BuildType](../../com.aspose.slides/buildtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

Powiązany efekt kształtu z grupą lub bez (null). Odczyt/zapis [IEffect](../../com.aspose.slides/ieffect).

**Zwraca:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

Powiązany efekt kształtu z grupą lub bez (null). Odczyt/zapis [IEffect](../../com.aspose.slides/ieffect).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |