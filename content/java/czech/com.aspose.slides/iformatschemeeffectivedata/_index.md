---
title: IFormatSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective format scheme properties.
type: docs
url: /cs/com.aspose.slides/iformatschemeeffectivedata/
---```
public interface IFormatSchemeEffectiveData
```

Neměnný objekt, který obsahuje vlastnosti efektivního schématu formátování.

--------------------

Toto rozhraní se používá jako součást [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Methods

| Metoda | Popis |
| --- | --- |
| [getFillStyles(Color styleColor)](#getFillStyles-java.awt.Color-) | Vrací kolekci stylů výplní definovaných v tématu. |
| [getLineStyles(Color styleColor)](#getLineStyles-java.awt.Color-) | Vrací kolekci stylů čar definovaných v tématu. |
| [getEffectStyles(Color styleColor)](#getEffectStyles-java.awt.Color-) | Vrací kolekci stylů efektů definovaných v tématu. |
| [getBackgroundFillStyles(Color styleColor)](#getBackgroundFillStyles-java.awt.Color-) | Vrací kolekci stylů výplní pozadí definovaných v tématu. |
### getFillStyles(Color styleColor) {#getFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getFillStyles(Color styleColor)
```

Vrací kolekci stylů výplní definovaných v tématu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Vrací:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Collection of effective fill formats [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)
### getLineStyles(Color styleColor) {#getLineStyles-java.awt.Color-}
```
public abstract ILineFormatCollectionEffectiveData getLineStyles(Color styleColor)
```

Vrací kolekci stylů čar definovaných v tématu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Vrací:**
[ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata) - Collection of effective line formats [ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata)
### getEffectStyles(Color styleColor) {#getEffectStyles-java.awt.Color-}
```
public abstract IEffectStyleCollectionEffectiveData getEffectStyles(Color styleColor)
```

Vrací kolekci stylů efektů definovaných v tématu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Vrací:**
[IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata) - Collection of effective effect styles [IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata)
### getBackgroundFillStyles(Color styleColor) {#getBackgroundFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getBackgroundFillStyles(Color styleColor)
```

Vrací kolekci stylů výplní pozadí definovaných v tématu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Vrací:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Collection of effective background fill formats [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)