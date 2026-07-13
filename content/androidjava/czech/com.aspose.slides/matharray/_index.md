---
title: MathArray
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Určuje svislé pole rovnic nebo jakýchkoli matematických objektů
type: docs
url: /cs/com.aspose.slides/matharray/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Určuje svislé pole rovnic nebo jakýchkoli matematických objektů

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Vytvoří matematické pole a umístí do něj zadaný prvek |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Vytvoří matematické pole a umístí do něj zadané prvky |
## Metody

| Metoda | Popis |
| --- | --- |
| [getArguments()](#getArguments--) | Množina položek pole |
| [getBaseJustification()](#getBaseJustification--) | Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán na spodek, vrchol nebo střed objektu pole. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán na spodek, vrchol nebo střed objektu pole. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximální distribuce. Když je true, pole je rozprostřeno na maximální šířku obsahujícího prvku (stránka, sloupec, buňka atd.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximální distribuce. Když je true, pole je rozprostřeno na maximální šířku obsahujícího prvku (stránka, sloupec, buňka atd.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribuce objektu. Když je true, obsah pole je rozprostřen na maximální šířku objektu pole. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribuce objektu. Když je true, obsah pole je rozprostřen na maximální šířku objektu pole. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Typ svislého odsazení mezi položkami pole. Výchozí: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Typ svislého odsazení mezi položkami pole. Výchozí: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Odsazení mezi řádky pole. Používá se pouze když je RowSpacingRule nastaven na 3. V takovém případě je jednotkou měření body nebo při nastavení Multiple jsou to půlřádky. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Odsazení mezi řádky pole. Používá se pouze když je RowSpacingRule nastaven na 3. V takovém případě je jednotkou měření body nebo při nastavení Multiple jsou to půlřádky. |
| [getChildren()](#getChildren--) | Získá podřízené prvky |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```


Vytvoří matematické pole a umístí do něj zadaný prvek

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Prvek, který bude umístěn do pole |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```


Vytvoří matematické pole a umístí do něj zadané prvky

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Prvky, které budou umístěny do pole |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


Množina položek pole

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Vrací:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán na spodek, vrchol nebo střed objektu pole. Výchozí hodnota: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Vrací:** 
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```


Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán na spodek, vrchol nebo střed objektu pole. Výchozí hodnota: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```


Maximální distribuce. Když je true, pole je rozprostřeno na maximální šířku obsahujícího prvku (stránka, sloupec, buňka atd.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Vrací:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```


Maximální distribuce. Když je true, pole je rozprostřeno na maximální šířku obsahujícího prvku (stránka, sloupec, buňka atd.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```


Distribuce objektu. Když je true, obsah pole je rozprostřen na maximální šířku objektu pole.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Vrací:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```


Distribuce objektu. Když je true, obsah pole je rozprostřen na maximální šířku objektu pole.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```


Typ svislého odsazení mezi položkami pole. Výchozí: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Vrací:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```


Typ svislého odsazení mezi položkami pole. Výchozí: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```


Odsazení mezi řádky pole. Používá se pouze když je RowSpacingRule nastaven na 3. V takovém případě je jednotkou měření body nebo při nastavení Multiple jsou to půlřádky. Výchozí: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Vrací:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```


Odsazení mezi řádky pole. Používá se pouze když je RowSpacingRule nastaven na 3. V takovém případě je jednotkou měření body nebo při nastavení Multiple jsou to půlřádky. Výchozí: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získá podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]