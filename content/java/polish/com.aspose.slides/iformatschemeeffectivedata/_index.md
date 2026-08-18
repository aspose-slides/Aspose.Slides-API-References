---
title: IFormatSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective format scheme properties.
type: docs
url: /pl/com.aspose.slides/iformatschemeeffectivedata/
---```
public interface IFormatSchemeEffectiveData
```

Niezmienny obiekt zawierający efektywne właściwości schematu formatu.

--------------------

Ten interfejs jest używany jako część [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getFillStyles(Color styleColor)](#getFillStyles-java.awt.Color-) | Returns a collection of theme defined fill styles. |
| [getLineStyles(Color styleColor)](#getLineStyles-java.awt.Color-) | Returns a collection of theme defined line styles. |
| [getEffectStyles(Color styleColor)](#getEffectStyles-java.awt.Color-) | Returns a collection of theme defined effect styles. |
| [getBackgroundFillStyles(Color styleColor)](#getBackgroundFillStyles-java.awt.Color-) | Returns a collection of theme defined background fill styles. |
### getFillStyles(Color styleColor) {#getFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getFillStyles(Color styleColor)
```

Zwraca kolekcję stylów wypełnienia zdefiniowanych w motywie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Zwraca:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Kolekcja efektywnych formatów wypełnienia [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)
### getLineStyles(Color styleColor) {#getLineStyles-java.awt.Color-}
```
public abstract ILineFormatCollectionEffectiveData getLineStyles(Color styleColor)
```

Zwraca kolekcję stylów linii zdefiniowanych w motywie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Zwraca:**
[ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata) - Kolekcja efektywnych formatów linii [ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata)
### getEffectStyles(Color styleColor) {#getEffectStyles-java.awt.Color-}
```
public abstract IEffectStyleCollectionEffectiveData getEffectStyles(Color styleColor)
```

Zwraca kolekcję stylów efektów zdefiniowanych w motywie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Zwraca:**
[IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata) - Kolekcja efektywnych formatów efektów [IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata)
### getBackgroundFillStyles(Color styleColor) {#getBackgroundFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getBackgroundFillStyles(Color styleColor)
```

Zwraca kolekcję stylów wypełnienia tła zdefiniowanych w motywie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Zwraca:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Kolekcja efektywnych formatów wypełnienia tła [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)