---
title: MathBlock
second_title: Java API Referansı ile Android için Aspose.Slides
description: Bir MathParagraph içinde bulunan ve kendi satırında başlayan matematik metni örneğini belirtir.
type: docs
url: /tr/com.aspose.slides/mathblock/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Bir MathParagraph içinde bulunan ve kendi satırında başlayan matematik metni örneğini belirtir. Denklemler, ifadeler, denklemlerin veya ifadelerin dizileri ve formüller dahil olmak üzere tüm matematik bölgeleri bir math block tarafından temsil edilir.

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
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeyi içine koyar. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeleri içine koyar. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyonda gerçekten bulunan alt matematik öğelerinin sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki IMathElement'i alır veya ayarlar. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Belirtilen indeksteki IMathElement'i alır veya ayarlar. |
| [isReadOnly()](#isReadOnly--) | Alt öğe koleksiyonu değiştirilebilir olduğu için false döndürür. |
| [getChildren()](#getChildren--) | Alt öğeleri al. |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate nesnesini döndürür. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Koleksiyonun sonuna bir matematik öğesi ekler. |
| [clear()](#clear--) | Koleksiyondan tüm öğeleri kaldırır. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Belirtilen diziye kopyalar. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Koleksiyondaki belirli bir matematik öğesinin indeksini belirler. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Belirtilen indekste koleksiyona bir MathElement ekler. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonun belirtilen indeksindeki öğeyi kaldırır. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Bir matematik öğesini bu matematik bloğu ile birleştirir |
| [join(String mathText)](#join-java.lang.String-) | Bir matematik metnini bu matematik bloğu ile birleştirir |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Başka bir matematik bloğunu bu bloğa birleştirir |
| [delimit(char separatorCharacter)](#delimit-char-) | Alt öğeleri ayraç karakteriyle (köşeli parantezsiz) sınırlıyor |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerde çerçeveleyerek kapsar |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerde çerçeveleyerek kapsar ve bir ayraç karakteriyle sınırlar |
| [toMathArray()](#toMathArray--) | Alt öğeleri dikey bir diziye yerleştirir |
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

Yeni bir matematik bloğu oluşturur ve belirtilen öğeyi içine koyar.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Bloğa konulacak matematik öğesi. |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Yeni bir matematik bloğu oluşturur ve belirtilen öğeleri içine koyar.

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
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Bloğa konulacak matematik öğeleri. |

### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyonda gerçekten bulunan alt matematik öğelerinin sayısını alır. Salt-okunur int.

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
| index | int | Öğenin sıfır tabanlı indeksi. |

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
| index | int | Öğenin sıfır tabanlı indeksi. |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Matematik öğesi. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Alt öğe koleksiyonu değiştirilebilir olduğu için false döndürür.

**Döndürür:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Alt öğeleri al.

**Döndürür:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Koleksiyonun sonuna bir matematik öğesi ekler.

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

Koleksiyondan tüm öğeleri kaldırır.

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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Koleksiyon içinde bulunacak nesne. |

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
boolean - öğe koleksiyondan başarıyla kaldırılmışsa true; aksi takdirde false. Bu yöntem ayrıca öğe orijinal koleksiyonda bulunamazsa false döndürür.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
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
> Örnek:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Koleksiyon içinde bulunacak öğe. |

**Döndürür:**
int - öğenin koleksiyonda bulunursa indeksi; aksi takdirde -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Belirtilen indekste koleksiyona bir MathElement ekler.

--------------------

> ```
> Örnek:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | MathElement'in eklenmesi gereken sıfır tabanlı indeks. |
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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Birleştirilecek öğe. |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - IMathBlock'un mevcut örneği
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Bir matematik metnini bu matematik bloğu ile birleştirir

--------------------

> ```
> Örnek:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | Birleştirilecek matematik metni. |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - Bu örneği ve belirtilen argümanı içeren yeni bir IMathBlock.
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Başka bir matematik bloğunu bu bloğa birleştirir

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
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Birleştirilen blok. |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - birleştirme sonrası bu matematik bloğu.
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Alt öğeleri ayraç karakteriyle (köşeli parantezsiz) sınırlıyor

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
| separatorCharacter | char | Ayraç karakteri |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) türünde matematik öğesi
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerde çerçeveleyerek kapsar

--------------------

> ```
> Örnek:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char | Başlangıç karakteri (genellikle sol parantez) |
| endingCharacter | char | Bitiş karakteri (genellikle sağ parantez) |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) türünde, belirtilen karakterleri çerçeveleyen bir matematik öğesi
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerde çerçeveleyerek kapsar ve bir ayraç karakteriyle sınırlar

--------------------

> ```
> Örnek:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char | Başlangıç karakteri (genellikle sol parantez) |
| endingCharacter | char | Bitiş karakteri (genellikle sağ parantez) |
| separatorCharacter | char | Ayraç karakteri |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) türünde, belirtilen karakterleri çerçeve ve ayraç olarak içeren bir matematik öğesi
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Alt öğeleri dikey bir diziye yerleştirir

--------------------

> ```
> Örnek:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Döndürür:**
[IMathArray](../../com.aspose.slides/imatharray) - [IMathArray](../../com.aspose.slides/imatharray) türünde yeni bir örnek
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Bu [MathBlock](../../com.aspose.slides/mathblock) içeriğini MathML olarak kaydeder

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |