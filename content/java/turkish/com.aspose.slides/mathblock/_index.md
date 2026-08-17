---
title: MathBlock
second_title: Aspose.Slides for Java API Referansı
description: Bir MathParagraph içinde bulunan ve kendi satırında başlayan matematiksel metin örneğini belirler.
type: docs
url: /tr/com.aspose.slides/mathblock/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Bir MathParagraph içinde bulunan ve kendi satırında başlayan matematiksel metin örneğini belirtir. Tüm matematik bölgeleri, denklemler, ifadeler, denklemlerin veya ifadelerin dizileri ve formüller dahil olmak üzere, math block ile temsil edilir.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathBlock()](#MathBlock--) | MathBlock sınıfının yeni bir örneğini başlatır. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeyi içine ekler |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeleri içine ekler |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan alt matematik öğelerinin sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki IMathElement'i alır veya ayarlar. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Belirtilen indeksteki IMathElement'i alır veya ayarlar. |
| [isReadOnly()](#isReadOnly--) | Alt öğe koleksiyonu değiştirilebilir olduğu için false döndürür. |
| [getChildren()](#getChildren--) | Alt öğeleri al. |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate nesnesini döndürür. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Bir matematik öğesini koleksiyonun sonuna ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copy to specified array. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Koleksiyondaki belirli bir matematik öğesinin indeksini belirler. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Belirtilen indekste bir MathElement'i koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonun belirtilen indeksindeki öğeyi kaldırır. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Bir matematik öğesini bu matematik bloğuna birleştirir |
| [join(String mathText)](#join-java.lang.String-) | Bir matematik metnini bu matematik bloğuyla birleştirir |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Başka bir matematik bloğunu bu blokla birleştirir |
| [delimit(char separatorCharacter)](#delimit-char-) | Alt öğeleri ayırıcı karakterle (köşeli parantezler olmadan) sınırlar |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bu bloğun alt öğelerini parantez veya başka karakterler gibi belirlenen karakterlerle çerçeveler |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Bu bloğun alt öğelerini parantez veya başka karakterler gibi belirlenen karakterlerle çerçeveler ve ayırıcı karakterle sınırlar |
| [toMathArray()](#toMathArray--) | Alt öğeleri dikey bir diziye koyar |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Bu [MathBlock](../../com.aspose.slides/mathblock) içeriğini MathML olarak kaydeder |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

MathBlock sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

Yeni bir matematik bloğu oluşturur ve belirtilen öğeyi içine ekler

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Bloka yerleştirilecek matematik öğesi |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Yeni bir matematik bloğu oluşturur ve belirtilen öğeleri içine ekler

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Bloğa yerleştirilecek matematik öğeleri |

### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyonda gerçekte bulunan alt matematik öğelerinin sayısını alır. Yalnızca okunabilir int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Belirtilen indeksteki IMathElement'i alır veya ayarlar.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin sıfır tabanlı indeksi |

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement) - Matematik öğesi.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Belirtilen indeksteki IMathElement'i alır veya ayarlar.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin sıfır tabanlı indeksi |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Matematik öğesi. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Yalnızca okunabilir olduğu için false döndürür.

**Döndürür:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Alt öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunabilir IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Bir matematik öğesini koleksiyonun sonuna ekler.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Koleksiyonun sonuna eklenecek IMathElement. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

Koleksiyonun belirli bir değeri içerip içermediğini belirler.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Koleksiyonda bulunacak nesne. |

**Döndürür:**
boolean - öğe koleksiyonda bulunursa true; aksi takdirde false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Belirtilen diziye kopyalar.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Kopyalanacak dizi. |
| arrayIndex | int | Kopyalamaya başlanacak indeks. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Koleksiyondan kaldırılacak nesne. |

**Döndürür:**
boolean - öğe başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem, öğe orijinal koleksiyonda bulunmazsa da false döndürür.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Koleksiyon içinde yineleme yapılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.IEnumerator - Tüm koleksiyon için bir java.util.Iterator.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Koleksiyondaki belirli bir matematik öğesinin indeksini belirler.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Koleksiyonda bulunacak öğe. |

**Döndürür:**
int - öğe koleksiyonda bulunursa indeksi; aksi takdirde -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Belirtilen indekste bir MathElement'i koleksiyona ekler.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | MathElement'in ekleneceği sıfır tabanlı indeks. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Eklenecek MathElement. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Koleksiyonun belirtilen indeksindeki öğeyi kaldırır.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Bir matematik öğesini bu matematik bloğu ile birleştirir

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Birleştirilecek öğe |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - IMathBlock'un mevcut örneği
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Bir matematik metnini bu matematik bloğu ile birleştirir

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | Birleştirilecek matematik metni |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - Bu örnek ve belirtilen argümanı içeren yeni bir IMathBlock
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Başka bir matematik bloğunu bu blokla birleştirir

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Birleştirilen blok |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - Birleştirmeden sonra bu matematik bloğu
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Alt öğeleri ayırıcı karakterle (köşeli parantezler olmadan) sınırlar

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separatorCharacter | char | Ayırıcı karakter |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) tipinde matematik öğesi
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Bu bloğun alt öğelerini parantez veya başka karakterler gibi belirlenen karakterlerle çerçeveler

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char | Başlangıç karakteri (genellikle sol köşeli parantez) |
| endingCharacter | char | Bitiş karakteri (genellikle sağ köşeli parantez) |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) tipinde, belirtilen karakterleri çerçeveleyen matematik öğesi
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Bu bloğun alt öğelerini parantez veya başka karakterler gibi belirlenen karakterlerle çerçeveler ve ayırıcı karakterle sınırlar

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char | Başlangıç karakteri (genellikle sol köşeli parantez) |
| endingCharacter | char | Bitiş karakteri (genellikle sağ köşeli parantez) |
| separatorCharacter | char | Ayırıcı karakter |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) tipinde, belirtilen karakterleri çerçeveleyen ve ayırıcı karakteri içeren matematik öğesi
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Alt öğeleri dikey bir diziye koyar

--------------------

> ```
> Örnek:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Döndürür:**
[IMathArray](../../com.aspose.slides/imatharray) - [IMathArray](../../com.aspose.slides/imatharray) tipinde yeni bir örnek
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Bu [MathBlock](../../com.aspose.slides/mathblock) içeriğini MathML olarak kaydeder

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |