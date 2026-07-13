---
title: MathArray
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert een verticale array van vergelijkingen of andere wiskundige objecten
type: docs
url: /nl/com.aspose.slides/matharray/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Specificeert een verticale array van vergelijkingen of andere wiskundige objecten

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Maakt een wiskundige array en plaatst het opgegeven element erin |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Maakt een wiskundige array en plaatst opgegeven elementen erin |
## Methods

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | De verzameling items van de array |
| [getBaseJustification()](#getBaseJustification--) | Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan uitgelijnd worden met de onderkant, bovenkant of het midden van een array-object. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan uitgelijnd worden met de onderkant, bovenkant of het midden van een array-object. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum distributie: wanneer true, wordt de array uitgelijnd tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum distributie: wanneer true, wordt de array uitgelijnd tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.). |
| [getObjectDistribution()](#getObjectDistribution--) | Objectdistributie: wanneer true, worden de inhoud van de array uitgelijnd tot de maximale breedte van het array-object. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Objectdistributie: wanneer true, worden de inhoud van de array uitgelijnd tot de maximale breedte van het array-object. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Het type verticale spatiëring tussen array-elementen. Standaard: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Het type verticale spatiëring tussen array-elementen. Standaard: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Spatiëring tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3. In dat geval is de eenheid points, of Multiple waarbij de eenheid half-regels is. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Spatiëring tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3. In dat geval is de eenheid points, of Multiple waarbij de eenheid half-regels is. |
| [getChildren()](#getChildren--) | Haalt kind-elementen op |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Maakt een wiskundige array en plaatst het opgegeven element erin

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het element om in de array te plaatsen |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Maakt een wiskundige array en plaatst opgegeven elementen erin

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elementen om in de array te plaatsen |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

De verzameling items van de array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Retour:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan uitgelijnd worden met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Retour:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan uitgelijnd worden met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

Maximum distributie: wanneer true, wordt de array uitgelijnd tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Retour:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Maximum distributie: wanneer true, wordt de array uitgelijnd tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

Objectdistributie: wanneer true, worden de inhoud van de array uitgelijnd tot de maximale breedte van het array-object.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Retour:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Objectdistributie: wanneer true, worden de inhoud van de array uitgelijnd tot de maximale breedte van het array-object.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

Het type verticale spatiëring tussen array-elementen. Standaard: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Retour:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

Het type verticale spatiëring tussen array-elementen. Standaard: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

Spatiëring tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3. In dat geval is de eenheid points, of Multiple waarbij de eenheid half-regels is. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Retour:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

Spatiëring tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3. In dat geval is de eenheid points, of Multiple waarbij de eenheid half-regels is. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Haalt kind-elementen op

**Retour:**
com.aspose.slides.IMathElement[]