---
title: IMathArray
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Určuje svislé pole rovnic nebo jakýchkoli matematických objektů
type: docs
url: /cs/com.aspose.slides/imatharray/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Určuje svislé pole rovnic nebo jakýchkoli matematických objektů

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getArguments()](#getArguments--) | Množina položek pole |
| [getBaseJustification()](#getBaseJustification--) | Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán na spodní, horní nebo střední část objektu pole. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán na spodní, horní nebo střední část objektu pole. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximální distribuce. Když je true, pole je roztahováno na maximální šířku obsahujícího prvku (stránka, sloupec, buňka atd.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximální distribuce. Když je true, pole je roztahováno na maximální šířku obsahujícího prvku (stránka, sloupec, buňka atd.). |
| [getObjectDistribution()](#getObjectDistribution--) | Rozdělení objektu. Když je true, obsah pole je roztahován na maximální šířku objektu pole. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Rozdělení objektu. Když je true, obsah pole je roztahován na maximální šířku objektu pole. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Typ svislého rozestupu mezi prvky pole |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Typ svislého rozestupu mezi prvky pole |
| [getRowSpacing()](#getRowSpacing--) | Rozestup mezi řádky pole. Používá se pouze když je RowSpacingRule nastaven na 3. V takovém případě je jednotkou měření body nebo Multiple, kde jednotkou je půlřádka. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Rozestup mezi řádky pole. Používá se pouze když je RowSpacingRule nastaven na 3. V takovém případě je jednotkou měření body nebo Multiple, kde jednotkou je půlřádka. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Množina položek pole

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
>  ```

**Vrací:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán na spodní, horní nebo střední část objektu pole. Výchozí hodnota: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
>  ```

**Vrací:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán na spodní, horní nebo střední část objektu pole. Výchozí hodnota: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
>  ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Maximální distribuce. Když je true, pole je roztahováno na maximální šířku obsahujícího prvku (stránka, sloupec, buňka atd.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
>  ```

**Vrací:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Maximální distribuce. Když je true, pole je roztahováno na maximální šířku obsahujícího prvku (stránka, sloupec, buňka atd.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
>  ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Rozdělení objektu. Když je true, obsah pole je roztahován na maximální šířku objektu pole.

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
public abstract void setObjectDistribution(boolean value)
```

Rozdělení objektu. Když je true, obsah pole je roztahován na maximální šířku objektu pole.

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
public abstract int getRowSpacingRule()
```

Typ svislého rozestupu mezi prvky pole

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
public abstract void setRowSpacingRule(int value)
```

Typ svislého rozestupu mezi prvky pole

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
public abstract long getRowSpacing()
```

Rozestup mezi řádky pole. Používá se pouze když je RowSpacingRule nastaven na 3. V takovém případě je jednotkou měření body nebo Multiple, kde jednotkou je půlřádka. Výchozí: 0

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
public abstract void setRowSpacing(long value)
```

Rozestup mezi řádky pole. Používá se pouze když je RowSpacingRule nastaven na 3. V takovém případě je jednotkou měření body nebo Multiple, kde jednotkou je půlřádka. Výchozí: 0

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