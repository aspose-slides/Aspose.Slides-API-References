---
title: IMathArray
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert een verticale array van vergelijkingen of andere wiskundige objecten
type: docs
url: /nl/com.aspose.slides/imatharray/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Specificeert een verticale array van vergelijkingen of andere wiskundige objecten

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getArguments()](#getArguments--) | De set van items van de array |
| [getBaseJustification()](#getBaseJustification--) | Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximumdistributie. Wanneer true, wordt de array uitgevuld tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximumdistributie. Wanneer true, wordt de array uitgevuld tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.). |
| [getObjectDistribution()](#getObjectDistribution--) | Objectdistributie. Wanneer true, wordt de inhoud van de array uitgevuld tot de maximale breedte van het array-object. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Objectdistributie. Wanneer true, wordt de inhoud van de array uitgevuld tot de maximale breedte van het array-object. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Het type verticale tussenruimte tussen array-elementen |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Het type verticale tussenruimte tussen array-elementen |
| [getRowSpacing()](#getRowSpacing--) | Tussenruimte tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3, Exact: in dat geval is de meeteenheid punten, of Multiple: in dat geval is de meeteenheid halve regels. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Tussenruimte tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3, Exact: in dat geval is de meeteenheid punten, of Multiple: in dat geval is de meeteenheid halve regels. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

De set van items van de array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
>  ```

**Retour:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center

--------------------

> ```
> Voorbeeld:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Retour:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center

--------------------

> ```
> Voorbeeld:
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
public abstract boolean getMaximumDistribution()
```

Maximumdistributie. Wanneer true, wordt de array uitgevuld tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.).

--------------------

> ```
> Voorbeeld:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Retour:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Maximumdistributie. Wanneer true, wordt de array uitgevuld tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.).

--------------------

> ```
> Voorbeeld:
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
public abstract boolean getObjectDistribution()
```

Objectdistributie. Wanneer true, wordt de inhoud van de array uitgevuld tot de maximale breedte van het array-object.

--------------------

> ```
> Voorbeeld:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Retour:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Objectdistributie. Wanneer true, wordt de inhoud van de array uitgevuld tot de maximale breedte van het array-object.

--------------------

> ```
> Voorbeeld:
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
public abstract int getRowSpacingRule()
```

Het type verticale tussenruimte tussen array-elementen

--------------------

> ```
> Voorbeeld:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Retour:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

Het type verticale tussenruimte tussen array-elementen

--------------------

> ```
> Voorbeeld:
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
public abstract long getRowSpacing()
```

Tussenruimte tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3, Exact: in dat geval is de meeteenheid punten, of Multiple: in dat geval is de meeteenheid halve regels. Standaard: 0

--------------------

> ```
> Voorbeeld:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Retour:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Tussenruimte tussen rijen van een array. Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3, Exact: in dat geval is de meeteenheid punten, of Multiple: in dat geval is de meeteenheid halve regels. Standaard: 0

--------------------

> ```
> Voorbeeld:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |