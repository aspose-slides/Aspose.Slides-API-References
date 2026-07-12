---
title: MathArray
second_title: Aspose.Slides Android için Java API Referansı
description: Denklemlerin veya herhangi bir matematiksel nesnenin dikey dizisini belirtir
type: docs
url: /tr/com.aspose.slides/matharray/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Denklemlerin veya herhangi bir matematiksel nesnenin dikey dizisini belirtir

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Bir matematik dizisi oluşturur ve belirtilen öğeyi içine yerleştirir |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Bir matematik dizisi oluşturur ve belirtilen öğeleri içine yerleştirir |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getArguments()](#getArguments--) | Dizinin öğe kümesi |
| [getBaseJustification()](#getBaseJustification--) | Dizinin çevre metne göre hizalamasını belirler. Dizinin dışındaki metin, dizi nesnesinin altına, üstüne veya ortasına hizalanabilir. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Dizinin çevre metne göre hizalamasını belirler. Dizinin dışındaki metin, dizi nesnesinin altına, üstüne veya ortasına hizalanabilir. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maksimum Dağıtım. Doğru olduğunda, dizi kapsayan öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre yerleştirilir. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maksimum Dağıtım. Doğru olduğunda, dizi kapsayan öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre yerleştirilir. |
| [getObjectDistribution()](#getObjectDistribution--) | Nesne Dağıtımı. Doğru olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre yerleştirilir. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Nesne Dağıtımı. Doğru olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre yerleştirilir. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Dizi öğeleri arasındaki dikey boşluk türü. Varsayılan: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Dizi öğeleri arasındaki dikey boşluk türü. Varsayılan: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Bir dizinin satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır; bu durumda ölçü birimi puan, Multiple olduğunda ölçü birimi yarı satırdır. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Bir dizinin satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır; bu durumda ölçü birimi puan, Multiple olduğunda ölçü birimi yarı satırdır. |
| [getChildren()](#getChildren--) | Alt öğeleri al |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Bir matematik dizisi oluşturur ve belirtilen öğeyi içine yerleştirir

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Dizide yer alacak öğe |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Bir matematik dizisi oluşturur ve belirtilen öğeleri içine yerleştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Dizide yer alacak öğeler |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Dizinin öğe kümesi

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Döndürür:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Dizinin çevre metne göre hizalamasını belirler. Dizinin dışındaki metin, dizi nesnesinin altına, üstüne veya ortasına hizalanabilir. Varsayılan değer: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Döndürür:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Dizinin çevre metne göre hizalamasını belirler. Dizinin dışındaki metin, dizi nesnesinin altına, üstüne veya ortasına hizalanabilir. Varsayılan değer: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

Maksimum Dağıtım. Doğru olduğunda, dizi kapsayan öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre yerleştirilir.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Döndürür:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Maksimum Dağıtım. Doğru olduğunda, dizi kapsayan öğenin (sayfa, sütun, hücre vb.) maksimum genişliğine göre yerleştirilir.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

Nesne Dağıtımı. Doğru olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre yerleştirilir.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Döndürür:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Nesne Dağıtımı. Doğru olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre yerleştirilir.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

Dizi öğeleri arasındaki dikey boşluk türü. Varsayılan: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Döndürür:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

Dizi öğeleri arasındaki dikey boşluk türü. Varsayılan: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

Bir dizinin satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır; bu durumda ölçü birimi puan, Multiple olduğunda ölçü birimi yarı satırdır. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Döndürür:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

Bir dizinin satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır; bu durumda ölçü birimi puan, Multiple olduğunda ölçü birimi yarı satırdır. Varsayılan: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Alt öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]