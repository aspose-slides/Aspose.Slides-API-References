---
title: IViewProperties
second_title: Aspose.Slides pro Android přes Java API Reference
description: Vlastnosti zobrazení pro celou prezentaci.
type: docs
url: /cs/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Vlastnosti zobrazení pro celou prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLastView()](#getLastView--) | Specifies the view mode that was used when the presentation document was last saved. |
| [setLastView(int value)](#setLastView-int-) | Specifies the view mode that was used when the presentation document was last saved. |
| [getShowComments()](#getShowComments--) | Specifies whether the slide comments should be shown. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specifies whether the slide comments should be shown. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specifies common view properties associated with the slide view mode. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specifies common view properties associated with the notes view mode. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Represents normal view properties. |
| [getGridSpacing()](#getGridSpacing--) | Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Určuje režim zobrazení, který byl použit, když byl dokument prezentace naposledy uložen. Čtení/Zápis [ViewType](../../com.aspose.slides/viewtype).

**Vrací:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Určuje režim zobrazení, který byl použit, když byl dokument prezentace naposledy uložen. Čtení/Zápis [ViewType](../../com.aspose.slides/viewtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Určuje, zda mají být zobrazeny komentáře ke snímkům. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Určuje, zda mají být zobrazeny komentáře ke snímkům. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Určuje společné vlastnosti zobrazení spojené s režimem zobrazení snímků. Pouze pro čtení [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Vrací:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Určuje společné vlastnosti zobrazení spojené s režimem zobrazení poznámek. Pouze pro čtení [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Vrací:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Reprezentuje vlastnosti normálního zobrazení. Normální zobrazení se skládá ze tří oblastí obsahu: samotného snímku, boční oblasti obsahu a spodní oblasti obsahu. Pouze pro čtení [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Vrací:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Vrací nebo nastavuje rozestup mřížky, který má být použit pro mřížku podkladu dokumentu prezentace, v bodech. Čtení/Zápis float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Hodnota rozestupu mřížky musí být kladné číslo. Typický rozsah hodnot je od 1 mm (2.8349607 bodů) do 2 palců (144 bodů).

**Vrací:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Vrací nebo nastavuje rozestup mřížky, který má být použit pro mřížku podkladu dokumentu prezentace, v bodech. Čtení/Zápis float.

--------------------

> ```
> Následující ukázkový kód ukazuje, jak změnit rozestup mřížky v prezentaci PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Hodnota rozestupu mřížky musí být kladné číslo. Typický rozsah hodnot je od 1 mm (2.8349607 bodů) do 2 palců (144 bodů).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |