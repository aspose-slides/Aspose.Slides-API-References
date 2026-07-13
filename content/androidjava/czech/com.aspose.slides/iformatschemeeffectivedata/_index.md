---
title: IFormatSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti formátovacího schématu.
type: docs
url: /cs/com.aspose.slides/iformatschemeeffectivedata/
---```
public interface IFormatSchemeEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti formátovacího schématu.

--------------------

This interface is used as a part of [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillStyles(Integer styleColor)](#getFillStyles-java.lang.Integer-) | Vrací kolekci stylů výplní definovaných tématem. |
| [getLineStyles(Integer styleColor)](#getLineStyles-java.lang.Integer-) | Vrací kolekci stylů čar definovaných tématem. |
| [getEffectStyles(Integer styleColor)](#getEffectStyles-java.lang.Integer-) | Vrací kolekci stylů efektů definovaných tématem. |
| [getBackgroundFillStyles(Integer styleColor)](#getBackgroundFillStyles-java.lang.Integer-) | Vrací kolekci stylů výplní pozadí definovaných tématem. |
### getFillStyles(Integer styleColor) {#getFillStyles-java.lang.Integer-}
```
public abstract IFillFormatCollectionEffectiveData getFillStyles(Integer styleColor)
```

Vrací kolekci stylů výplní definovaných tématem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.lang.Integer | Barva java.lang.Integer |

**Vrací:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Kolekce efektivních výplňových formátů [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)
### getLineStyles(Integer styleColor) {#getLineStyles-java.lang.Integer-}
```
public abstract ILineFormatCollectionEffectiveData getLineStyles(Integer styleColor)
```

Vrací kolekci stylů čar definovaných tématem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.lang.Integer | Barva java.lang.Integer |

**Vrací:**
[ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata) - Kolekce efektivních formátů čar [ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata)
### getEffectStyles(Integer styleColor) {#getEffectStyles-java.lang.Integer-}
```
public abstract IEffectStyleCollectionEffectiveData getEffectStyles(Integer styleColor)
```

Vrací kolekci stylů efektů definovaných tématem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.lang.Integer | Barva java.lang.Integer |

**Vrací:**
[IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata) - Kolekce efektivních formátů efektů [IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata)
### getBackgroundFillStyles(Integer styleColor) {#getBackgroundFillStyles-java.lang.Integer-}
```
public abstract IFillFormatCollectionEffectiveData getBackgroundFillStyles(Integer styleColor)
```

Vrací kolekci stylů výplní pozadí definovaných tématem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.lang.Integer | Barva java.lang.Integer |

**Vrací:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Kolekce efektivních formátů výplní pozadí [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)