---
title: MathBlock
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menentukan sebuah instance teks matematis yang berada dalam MathParagraph dan dimulai pada barisnya sendiri.
type: docs
url: /id/com.aspose.slides/mathblock/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Menentukan sebuah instance teks matematis yang berada dalam MathParagraph dan dimulai pada barisnya sendiri. Semua zona matematika, termasuk persamaan, ekspresi, array persamaan atau ekspresi, dan formula direpresentasikan oleh blok matematika.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathBlock()](#MathBlock--) | Menginisialisasi instance baru dari kelas MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Membuat blok matematika baru dan menempatkan elemen yang ditentukan di dalamnya |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Membuat blok matematika baru dan menempatkan elemen-elemen yang ditentukan di dalamnya |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen matematika anak yang sebenarnya terdapat dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan atau mengatur IMathElement pada indeks yang ditentukan. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Mendapatkan atau mengatur IMathElement pada indeks yang ditentukan. |
| [isReadOnly()](#isReadOnly--) | Mengembalikan false karena koleksi elemen anak dapat dimodifikasi. |
| [getChildren()](#getChildren--) | Mendapatkan elemen anak |
| [getParent_Immediate()](#getParent-Immediate--) | Mengembalikan objek Parent_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Menambahkan elemen matematika ke akhir koleksi. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Menentukan apakah koleksi berisi nilai tertentu. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Menyalin ke array yang ditentukan. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Menghapus kemunculan pertama objek tertentu dari koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Menentukan indeks elemen matematika tertentu dalam koleksi. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Menyisipkan MathElement ke dalam koleksi pada indeks yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Menggabungkan elemen matematika dengan blok matematika ini |
| [join(String mathText)](#join-java.lang.String-) | Menggabungkan teks matematika dengan blok matematika ini |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Menggabungkan blok matematika lain dengan blok ini |
| [delimit(char separatorCharacter)](#delimit-char-) | Membatasi elemen anak dengan karakter pemisah (tanpa tanda kurung) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Membungkus elemen anak blok ini dengan karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Membungkus elemen anak blok ini dengan karakter tertentu seperti tanda kurung atau lainnya sebagai bingkai dan membatasi dengan karakter pemisah |
| [toMathArray()](#toMathArray--) | Menempatkan elemen anak dalam array vertikal |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Menyimpan konten [MathBlock](../../com.aspose.slides/mathblock) ini sebagai MathML |

### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Menginisialisasi instance baru dari kelas MathBlock.

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

Membuat blok matematika baru dan menempatkan elemen yang ditentukan di dalamnya

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Elemen matematika yang akan ditempatkan dalam blok |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Membuat blok matematika baru dan menempatkan elemen-elemen yang ditentukan di dalamnya

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elemen matematika yang akan ditempatkan dalam blok |

### getCount() {#getCount--}
```
public final int getCount()
```

Mendapatkan jumlah elemen matematika anak yang sebenarnya terdapat dalam koleksi. int hanya-baca.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Mendapatkan atau mengatur IMathElement pada indeks yang ditentukan.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari item |

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement) - Elemen matematika.

### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Mendapatkan atau mengatur IMathElement pada indeks yang ditentukan.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari item |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Elemen matematika. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Mengembalikan false karena koleksi elemen anak dapat dimodifikasi.

**Mengembalikan:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Mendapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. IDOMObject hanya-baca.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Menambahkan elemen matematika ke akhir koleksi.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement yang akan ditambahkan ke akhir koleksi. |

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua elemen dari koleksi.

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

Menentukan apakah koleksi berisi nilai tertentu.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Objek yang akan dicari dalam koleksi. |

**Mengembalikan:**
boolean - true jika item ditemukan dalam koleksi; lainnya false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Menyalin ke array yang ditentukan.

--------------------

> ```
> Contoh:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array tujuan penyalinan. |
| arrayIndex | int | Indeks mulai menyalin. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Menghapus kemunculan pertama objek tertentu dari koleksi.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Objek yang akan dihapus dari koleksi. |

**Mengembalikan:**
boolean - true jika item berhasil dihapus dari koleksi; lainnya false. Metode ini juga mengembalikan false jika item tidak ditemukan dalam koleksi asli.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.IEnumerator - Sebuah java.util.Iterator untuk seluruh koleksi.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Menentukan indeks elemen matematika tertentu dalam koleksi.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang akan dicari dalam koleksi. |

**Mengembalikan:**
int - Indeks item jika ditemukan dalam koleksi; lainnya -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Menyisipkan MathElement ke dalam koleksi pada indeks yang ditentukan.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat MathElement akan disisipkan. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement yang akan disisipkan. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan dalam koleksi.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Menggabungkan elemen matematika dengan blok matematika ini

--------------------

> ```
> Contoh:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang akan digabungkan |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - Instansi saat ini dari IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Menggabungkan teks matematika dengan blok matematika ini

--------------------

> ```
> Contoh:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | java.lang.String | Teks matematika yang akan digabungkan |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - Sebuah IMathBlock baru yang berisi instansi ini dan argumen yang ditentukan
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Menggabungkan blok matematika lain dengan blok ini

--------------------

> ```
> Contoh:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Blok yang akan digabungkan |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika ini setelah digabungkan
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Membatasi elemen anak dengan karakter pemisah (tanpa tanda kurung)

--------------------

> ```
> Contoh:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separatorCharacter | char | Karakter pemisah |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Elemen matematika bertipe [IMathDelimiter](../../com.aspose.slides/imathdelimiter) yang mencakup karakter pemisah
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Membungkus elemen anak blok ini dengan karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char | Karakter pembuka (biasanya kurung kiri) |
| endingCharacter | char | Karakter penutup (biasanya kurung kanan) |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Elemen matematika bertipe [IMathDelimiter](../../com.aspose.slides/imathdelimiter) yang mencakup karakter yang ditentukan sebagai bingkai
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Membungkus elemen anak blok ini dengan karakter tertentu seperti tanda kurung atau lainnya sebagai bingkai dan membatasi dengan karakter pemisah

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char | Karakter pembuka (biasanya kurung kiri) |
| endingCharacter | char | Karakter penutup (biasanya kurung kanan) |
| separatorCharacter | char | Karakter pemisah |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Elemen matematika bertipe [IMathDelimiter](../../com.aspose.slides/imathdelimiter) yang mencakup karakter yang ditentukan sebagai bingkai dan pemisah
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Menempatkan elemen anak dalam array vertikal

--------------------

> ```
> Contoh:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Mengembalikan:**
[IMathArray](../../com.aspose.slides/imatharray) - Instansi baru bertipe [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Menyimpan konten [MathBlock](../../com.aspose.slides/mathblock) ini sebagai MathML

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream tujuan |