---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Presentation wide view properties.
type: docs
url: /cs/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Celkové vlastnosti zobrazení prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLastView()](#getLastView--) | Určuje režim zobrazení, který byl použit, když byl dokument prezentace naposledy uložen. |
| [setLastView(int value)](#setLastView-int-) | Určuje režim zobrazení, který byl použit, když byl dokument prezentace naposledy uložen. |
| [getShowComments()](#getShowComments--) | Určuje, zda se mají zobrazit komentáře ke snímkům. |
| [setShowComments(byte value)](#setShowComments-byte-) | Určuje, zda se mají zobrazit komentáře ke snímkům. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Určuje běžné vlastnosti zobrazení související s režimem zobrazení snímku. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Určuje běžné vlastnosti zobrazení související s režimem zobrazení poznámek. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Reprezentuje vlastnosti normálního zobrazení. |
| [getGridSpacing()](#getGridSpacing--) | Vrací nebo nastavuje rozestup mřížky, která by měla být použita pro mřížku podkládající dokument prezentace, v bodech. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Vrací nebo nastavuje rozestup mřížky, která by měla být použita pro mřížku podkládající dokument prezentace, v bodech. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Určuje, zda se mají zobrazit komentáře ke snímkům. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Určuje, zda se mají zobrazit komentáře ke snímkům. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Určuje běžné vlastnosti zobrazení související s režimem zobrazení snímku. Pouze pro čtení [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Vrací:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Určuje běžné vlastnosti zobrazení související s režimem zobrazení poznámek. Pouze pro čtení [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Vrací:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Reprezentuje vlastnosti normálního zobrazení. Normální zobrazení se skládá ze tří oblastí obsahu: samotného snímku, postranní oblasti obsahu a spodní oblasti obsahu. Pouze pro čtení [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Vrací:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Vrací nebo nastavuje rozestup mřížky, která by měla být použita pro mřížku podkládající dokument prezentace, v bodech. Čtení/Zápis float.

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

Hodnota rozestupu mřížky musí být kladné číslo. Typický rozsah hodnot je od 1 mm (2,8349607 bodu) do 2 palců (144 bodů).

**Vrací:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Vrací nebo nastavuje rozestup mřížky, která by měla být použita pro mřížku podkládající dokument prezentace, v bodech. Čtení/Zápis float.

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

Hodnota rozestupu mřížky musí být kladné číslo. Typický rozsah hodnot je od 1 mm (2,8349607 bodu) do 2 palců (144 bodů).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |