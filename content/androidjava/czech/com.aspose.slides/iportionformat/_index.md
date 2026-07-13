---
title: IPortionFormat
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Tato třída obsahuje vlastnosti formátování textových úseků.
type: docs
url: /cs/com.aspose.slides/iportionformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Tato třída obsahuje vlastnosti formátování textových úseků. Na rozdíl od [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

--------------------

Tato třída se používá k vrácení a manipulaci s vlastnostmi formátování textových úseků definovanými pro konkrétní úsek. To znamená, že při získávání hodnot se nepoužije dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [getEffective](../../com.aspose.slides/iportionformat\#getEffective), která vrací instanci [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Metody

| Metoda | Popis |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Vrací nebo nastavuje identifikátor záložky. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Vrací nebo nastavuje identifikátor záložky. |
| [getSmartTagClean()](#getSmartTagClean--) | Určuje, zda má být inteligentní značka vyčištěna. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Určuje, zda má být inteligentní značka vyčištěna. |
| [getEffective()](#getEffective--) | Získá efektivní data formátování úseku s aplikovanou dědičností. |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Vrací nebo nastavuje identifikátor záložky. Čtení/zápis String.

**Vrací:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Vrací nebo nastavuje identifikátor záložky. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Určuje, zda má být inteligentní značka vyčištěna. Dědičnost se nepoužívá. Čtení/zápis boolean.

**Vrací:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Určuje, zda má být inteligentní značka vyčištěna. Dědičnost se nepoužívá. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Získá efektivní data formátování úseku s aplikovanou dědičností.

**Vrací:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).