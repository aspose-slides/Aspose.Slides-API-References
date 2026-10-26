---
title: MathParagraph
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Matematik blokları için bir kapsayıcı olan matematik paragrafı IMathBlock
type: docs
url: /tr/com.aspose.slides/mathparagraph/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

Matematik blokları için bir kapsayıcı olan matematik paragrafı (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | MathParagraph sınıfının yeni bir örneğini başlatır. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | MathParagraph sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraf Hizalama Varsayılan değer: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraf Hizalama Varsayılan değer: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate nesnesini döndürür. |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan eleman sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki öğeyi alır. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Belirtilen indeksdeki öğeyi alır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | IMMathBlock'u koleksiyonun sonuna ekler. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | Koleksiyondaki belirli bir IMathBlock'un indeksini belirler. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | IMMathBlock'u belirtilen indekste koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen indeksteki öğeyi kaldırır. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Bu [MathParagraph](../../com.aspose.slides/mathparagraph) içeriğini MathML olarak kaydeder |
| [toLatex()](#toLatex--) | Matematiksel denklemi LaTeX biçiminde alır |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```


MathParagraph sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
> ```

### MathParagraph(IMathBlock mathBlock) {#MathParagraph-com.aspose.slides.IMathBlock-}
```
public MathParagraph(IMathBlock mathBlock)
```


MathParagraph sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```


Paragraf Hizalama Varsayılan değer: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Döndürür:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```


Paragraf Hizalama Varsayılan değer: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```


Koleksiyonda gerçekte bulunan eleman sayısını alır. Salt okunur int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```


Belirtilen indeksdeki öğeyi alır. Salt okunur [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak öğenin sıfır-tabanlı indeksi |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - Matematiksel bir metin bloğu.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```


Belirtilen indeksteki öğeyi alır. Salt okunur [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak öğenin sıfır-tabanlı indeksi |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Matematiksel bir metin bloğu. |

### clear() {#clear--}
```
public final void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  mathParagraph.clear();
> ```

### add(IMathBlock mathBlock) {#add-com.aspose.slides.IMathBlock-}
```
public final void add(IMathBlock mathBlock)
```


IMMathBlock'u koleksiyonun sonuna ekler.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Koleksiyonun sonuna eklenecek bir matematik bloğu |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```


Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.remove(block);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Koleksiyondan kaldırılacak nesne. |

**Döndürür:**
boolean - mathBlock koleksiyondan başarılı bir şekilde kaldırıldıysa true; aksi takdirde false. Bu yöntem aynı zamanda mathBlock orijinal koleksiyonda bulunamazsa false döndürür.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```


Koleksiyonun belirli bir değeri içerip içermediğini belirler.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  boolean contains = mathParagraph.contains(block);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Koleksiyonda bulunacak nesne. |

**Döndürür:**
boolean - mathBlock koleksiyonda bulunursa true; aksi takdirde false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```


Koleksiyondaki belirli bir IMathBlock'un indeksini belirler.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  int index = mathParagraph.indexOf(block);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Koleksiyonda bulunacak öğe. |

**Döndürür:**
int - mathBlock bulunursa indeks; aksi takdirde -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```


IMMathBlock'u belirtilen indekste koleksiyona ekler.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin eklenmesi gereken sıfır-tabanlı indeks. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Eklenecek IMathBlock. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Koleksiyonda belirtilen indeksteki öğeyi kaldırır.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır-tabanlı indeksi. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```




**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```




**Döndürür:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```


Bu [MathParagraph](../../com.aspose.slides/mathparagraph) içeriğini MathML olarak kaydeder

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |

### toLatex() {#toLatex--}
```
public final String toLatex()
```


Matematiksel denklemi LaTeX biçiminde alır

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Döndürür:**
java.lang.String