---
title: ITextAnimation
second_title: Aspose.Slides dla Androida poprzez Java API Reference
description: Reprezentuje animację tekstu.
type: docs
url: /pl/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Reprezentuje animację tekstu.
## Metody

| Metoda | Opis |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Dodaje nowy efekt na koniec bieżącej sekwencji do końca grupowych animacji tekstu. |
| [getBuildType()](#getBuildType--) | Lista typu budowania (np. |
| [setBuildType(int value)](#setBuildType-int-) | Lista typu budowania (np. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Powiązany efekt kształtu z grupą lub bez (null) Odczyt/zapis [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Powiązany efekt kształtu z grupą lub bez (null) Odczyt/zapis [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Dodaje nowy efekt na koniec bieżącej sekwencji do końca grupowych animacji tekstu. Ważne tylko wtedy, gdy liczba akapitów tekstu jest równa lub większa od liczby efektów w tej grupie!

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
public abstract int getBuildType()
```

Lista typu budowania (np. akapit 1,2,3, wszystkie jednocześnie) animacji tekstu. Odczyt/zapis \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Zwraca:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Lista typu budowania (np. akapit 1,2,3, wszystkie jednocześnie) animacji tekstu. Odczyt/zapis \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Powiązany efekt kształtu z grupą lub bez (null) Odczyt/zapis [IEffect](../../com.aspose.slides/ieffect).

**Zwraca:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Powiązany efekt kształtu z grupą lub bez (null) Odczyt/zapis [IEffect](../../com.aspose.slides/ieffect).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |