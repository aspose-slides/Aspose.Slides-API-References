---
title: IFormatSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Megváltoztathatatlan objektum, amely a hatékony formátum séma tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/iformatschemeeffectivedata/
---```
public interface IFormatSchemeEffectiveData
```

Megváltoztathatatlan objektum, amely a hatékony formátum séma tulajdonságait tartalmazza.

--------------------

Ez az interfész a [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) részeként használatos.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFillStyles(Color styleColor)](#getFillStyles-java.awt.Color-) | Returns a collection of theme defined fill styles. |
| [getLineStyles(Color styleColor)](#getLineStyles-java.awt.Color-) | Returns a collection of theme defined line styles. |
| [getEffectStyles(Color styleColor)](#getEffectStyles-java.awt.Color-) | Returns a collection of theme defined effect styles. |
| [getBackgroundFillStyles(Color styleColor)](#getBackgroundFillStyles-java.awt.Color-) | Returns a collection of theme defined background fill styles. |
### getFillStyles(Color styleColor) {#getFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getFillStyles(Color styleColor)
```

Visszaad egy gyűjteményt a téma által definiált kitöltési stílusokról.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Visszatérési érték:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Collection of effective fill formats [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)
### getLineStyles(Color styleColor) {#getLineStyles-java.awt.Color-}
```
public abstract ILineFormatCollectionEffectiveData getLineStyles(Color styleColor)
```

Visszaad egy gyűjteményt a téma által definiált vonalstílusokról.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Visszatérési érték:**
[ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata) - Collection of effective line formats [ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata)
### getEffectStyles(Color styleColor) {#getEffectStyles-java.awt.Color-}
```
public abstract IEffectStyleCollectionEffectiveData getEffectStyles(Color styleColor)
```

Visszaad egy gyűjteményt a téma által definiált effektusstílusokról.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Visszatérési érték:**
[IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata) - Collection of effective effect styles [IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata)
### getBackgroundFillStyles(Color styleColor) {#getBackgroundFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getBackgroundFillStyles(Color styleColor)
```

Visszaad egy gyűjteményt a téma által definiált háttérkitöltési stílusokról.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Visszatérési érték:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Collection of effective background fill formats [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)