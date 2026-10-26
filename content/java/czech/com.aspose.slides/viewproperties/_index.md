---
title: ViewProperties
second_title: Aspose.Slides pro Java - reference API
description: Vlastnosti zobrazení po celé prezentaci.
type: docs
url: /cs/com.aspose.slides/viewproperties/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Vlastnosti zobrazení po celé prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLastView()](#getLastView--) | Určuje režim zobrazení, který byl použit, když byl dokument prezentace naposledy uložen. |
| [setLastView(int value)](#setLastView-int-) | Určuje režim zobrazení, který byl použit, když byl dokument prezentace naposledy uložen. |
| [getShowComments()](#getShowComments--) | Určuje, zda mají být zobrazeny komentáře snímků. |
| [setShowComments(byte value)](#setShowComments-byte-) | Určuje, zda mají být zobrazeny komentáře snímků. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Zastupuje vlastnosti normálního zobrazení. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Určuje společné vlastnosti zobrazení spojené s režimem zobrazení snímku. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Určuje společné vlastnosti zobrazení spojené s režimem zobrazení poznámek. |
| [getGridSpacing()](#getGridSpacing--) | Vrací nebo nastavuje rozestup mřížky, který má být použit pro mřížku podkladového dokumentu prezentace, v bodech. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Vrací nebo nastavuje rozestup mřížky, který má být použit pro mřížku podkladového dokumentu prezentace, v bodech. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

Určuje režim zobrazení, který byl použit, když byl dokument prezentace naposledy uložen. Čtení/zápis [ViewType](../../com.aspose.slides/viewtype).

**Návratová hodnota:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Určuje režim zobrazení, který byl použit, když byl dokument prezentace naposledy uložen. Čtení/zápis [ViewType](../../com.aspose.slides/viewtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Určuje, zda mají být zobrazeny komentáře snímků. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Návratová hodnota:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Určuje, zda mají být zobrazeny komentáře snímků. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Zastupuje vlastnosti normálního zobrazení. Normální zobrazení se skládá ze tří oblastí obsahu: samotného snímku, boční oblasti obsahu a spodní oblasti obsahu. Pouze pro čtení [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Návratová hodnota:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Určuje společné vlastnosti zobrazení spojené s režimem zobrazení snímku. Pouze pro čtení [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Návratová hodnota:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Určuje společné vlastnosti zobrazení spojené s režimem zobrazení poznámek. Pouze pro čtení [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Návratová hodnota:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Vrací nebo nastavuje rozestup mřížky, který má být použit pro mřížku podkladového dokumentu prezentace, v bodech. Čtení/zápis float.

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

**Návratová hodnota:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Vrací nebo nastavuje rozestup mřížky, který má být použit pro mřížku podkladového dokumentu prezentace, v bodech. Čtení/zápis float.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Návratová hodnota:**
com.aspose.slides.IDOMObject