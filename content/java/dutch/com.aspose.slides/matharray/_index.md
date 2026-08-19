---
title: MathArray
second_title: Aspose.Slides voor Java API-referentie
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

| Constructor | Beschrijving |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Maakt een wiskundige array en plaatst het opgegeven element erin |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Maakt een wiskundige array en plaatst opgegeven elementen erin |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getArguments()](#getArguments--) | De verzameling items van de array |
| [getBaseJustification()](#getBaseJustification--) | Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution. Wanneer true, wordt de array uitgespreid tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution. Wanneer true, wordt de array uitgespreid tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.). |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution. Wanneer true, worden de inhoud van de array uitgespreid tot de maximale breedte van het array-object. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution. Wanneer true, worden de inhoud van de array uitgespreid tot de maximale breedte van het array-object. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Het type verticale afstand tussen array-elementen. Standaard: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Het type verticale afstand tussen array-elementen. Standaard: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Afstand tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3; dan is de eenheid punten of, bij Multiple, halve regels. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Afstand tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3; dan is de eenheid punten of, bij Multiple, halve regels. |
| [getChildren()](#getChildren--) | Haal kindelementen op |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het element dat in de array moet worden geplaatst |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Maakt een wiskundige array en plaatst opgegeven elementen erin

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elementen die in de array moeten worden geplaatst |

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

**Returns:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Returns:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

Maximum Distribution. Wanneer true, wordt de array uitgespreid tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Returns:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Maximum Distribution. Wanneer true, wordt de array uitgespreid tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

Object Distribution. Wanneer true, worden de inhoud van de array uitgespreid tot de maximale breedte van het array-object.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Returns:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Object Distribution. Wanneer true, worden de inhoud van de array uitgespreid tot de maximale breedte van het array-object.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

Het type verticale afstand tussen array-elementen. Standaard: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Returns:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

Het type verticale afstand tussen array-elementen. Standaard: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

Afstand tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3; dan is de eenheid punten of, bij Multiple, halve regels. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Returns:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

Afstand tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3; dan is de eenheid punten of, bij Multiple, halve regels. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Haal kindelementen op

**Returns:**
com.aspose.slides.IMathElement[]