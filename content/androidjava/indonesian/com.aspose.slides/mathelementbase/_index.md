---
title: MathElementBase
second_title: Referensi API Java untuk Aspose.Slides di Android
description: Kelas dasar untuk IMathElement dengan implementasi beberapa metode yang umum untuk semua kelas yang diwarisi. Hanya untuk penggunaan internal.
type: docs
url: /id/com.aspose.slides/mathelementbase/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Kelas dasar untuk IMathElement dengan implementasi beberapa metode yang umum untuk semua kelas yang diwarisi. Hanya untuk penggunaan internal. Kelas yang diwarisi harus IMathElement.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Mengembalikan objek Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [join(String mathText)](#join-java.lang.String-) | Menggabungkan teks matematika dan membentuk blok matematika |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [divide(String denominator)](#divide-java.lang.String-) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [enclose()](#enclose--) | Membungkus elemen matematika dalam tanda kurung |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Membungkus elemen matematika dalam karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [function(String functionArgument)](#function-java.lang.String-) | Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Membuat subskrip |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Membuat subskrip |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Membuat superskrip |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Membuat superskrip |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat subskrip dan superskrip di kanan |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Membuat subskrip dan superskrip di kanan |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat subskrip dan superskrip di kiri |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Membuat subskrip dan superskrip di kiri |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [radical(String degree)](#radical-java.lang.String-) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Mengambil batas atas |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Mengambil batas atas |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Mengambil batas bawah |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Mengambil batas bawah |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat operator N-ary |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Membuat operator N-ary |
| [toMathArray()](#toMathArray--) | Menempatkan dalam susunan vertikal |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Mengambil integral |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Mengambil integral |
| [integral(int integralType)](#integral-int-) | Mengambil integral tanpa batas |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Mengambil integral |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Mengambil integral |
| [accent(char accentCharacter)](#accent-char-) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [overbar()](#overbar--) | Menetapkan bar di atas elemen ini |
| [underbar()](#underbar--) | Menetapkan bar di bawah elemen ini |
| [group()](#group--) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau yang lain |
| [toBorderBox()](#toBorderBox--) | Menempatkan elemen ini dalam kotak bingkai |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Menempatkan elemen ini dalam kotak bingkai |
| [toBox()](#toBox--) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau teks matematika lainnya. |
| [getChildren()](#getChildren--) | Mendapatkan elemen anak |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Menggabungkan elemen matematika dan membentuk blok matematika

--------------------

> ```
> Example:
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
[IMathBlock](../../com.aspose.slides/imathblock) - Sebuah IMathBlock baru yang berisi instance ini dan argumen yang ditentukan
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Menggabungkan teks matematika dan membentuk blok matematika

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | java.lang.String | Teks matematika yang akan digabungkan |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - Sebuah IMathBlock baru yang berisi instance ini dan argumen yang ditentukan
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Penyebut |

**Mengembalikan:**
[IMathFraction](../../com.aspose.slides/imathfraction) - pecahan baru
### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | java.lang.String | Penyebut |

**Mengembalikan:**
[IMathFraction](../../com.aspose.slides/imathfraction) - pecahan baru
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Penyebut |
| fractionType | int | Tipe pecahan: Bar, NoBar, Skewed, Linear |

**Mengembalikan:**
[IMathFraction](../../com.aspose.slides/imathfraction) - pecahan baru
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | java.lang.String | Penyebut |
| fractionType | int | Tipe pecahan: Bar, NoBar, Skewed, Linear |

**Mengembalikan:**
[IMathFraction](../../com.aspose.slides/imathfraction) - pecahan baru
### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Membungkus elemen matematika dalam tanda kurung

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Elemen matematika tipe [IMathDelimiter](../../com.aspose.slides/imathdelimiter) yang mencakup tanda kurung
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Membungkus elemen matematika dalam karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char | Karakter awal (biasanya kurung kiri) |
| endingCharacter | char | Karakter akhir (biasanya kurung kanan) |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Elemen matematika tipe [IMathDelimiter](../../com.aspose.slides/imathdelimiter) yang mencakup karakter yang ditentukan sebagai bingkai
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumen fungsi |

**Mengembalikan:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionArgument | java.lang.String | Argumen fungsi |

**Mengembalikan:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Mengambil fungsi tertentu menggunakan instance ini sebagai argumen

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Nama fungsi |

**Mengembalikan:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Mengambil fungsi tertentu menggunakan instance ini sebagai argumen

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionName | java.lang.String | Nama fungsi |

**Mengembalikan:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Mengambil fungsi tertentu menggunakan instance ini sebagai argumen

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | int | Salah satu tipe fungsi umum dengan satu argumen |

**Mengembalikan:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Mengambil fungsi tertentu menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Mengembalikan logaritma 'x' dengan basis '5'
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | int | Salah satu tipe fungsi umum dengan dua argumen: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumen tambahan tergantung pada tipe fungsi |

**Mengembalikan:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Mengambil fungsi tertentu menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Mengembalikan logaritma 'x' dengan basis '5'
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | int | Salah satu tipe fungsi umum dengan dua argumen: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Argumen tambahan tergantung pada tipe fungsi |

**Mengembalikan:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Membuat subskrip

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subskrip (indeks bawah di kanan) |

**Mengembalikan:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Elemen matematika baru tipe [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Membuat subskrip

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | java.lang.String | Subskrip (indeks bawah di kanan) |

**Mengembalikan:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Elemen matematika baru tipe [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Membuat superskrip

--------------------

> ```
> Contoh:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superskrip (indeks atas di kanan) |

**Mengembalikan:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Elemen matematika baru tipe [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Membuat superskrip

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| superscript | java.lang.String | Superskrip (indeks atas di kanan) |

**Mengembalikan:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Elemen matematika baru tipe [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Membuat subskrip dan superskrip di kanan

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subskrip (indeks bawah di kanan) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superskrip (indeks atas di kanan) |

**Mengembalikan:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Elemen matematika baru tipe [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Membuat subskrip dan superskrip di kanan

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | java.lang.String | Subskrip (indeks bawah di kanan) |
| superscript | java.lang.String | Superskrip (indeks atas di kanan) |

**Mengembalikan:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Elemen matematika baru tipe [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Membuat subskrip dan superskrip di kiri

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subskrip (indeks bawah di kiri) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superskrip (indeks atas di kiri) |

**Mengembalikan:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Elemen matematika baru tipe [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Membuat subskrip dan superskrip di kiri

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | java.lang.String | Subskrip (indeks bawah di kiri) |
| superscript | java.lang.String | Superskrip (indeks atas di kiri) |

**Mengembalikan:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Elemen matematika baru tipe [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argumen akar |

**Mengembalikan:**
[IMathRadical](../../com.aspose.slides/imathradical) - Instance baru tipe [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| degree | java.lang.String | Argumen akar |

**Mengembalikan:**
[IMathRadical](../../com.aspose.slides/imathradical) - Instance baru tipe [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Mengambil batas atas

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | batas |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Instance baru tipe [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Mengambil batas atas

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | java.lang.String | batas |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Instance baru tipe [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Mengambil batas bawah

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | batas |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Instance baru tipe [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Mengambil batas bawah

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | java.lang.String | batas |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Instance baru tipe [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Membuat operator N-ary

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Tipe operator N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas bawah |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas atas |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instance baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Membuat operator N-ary

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Tipe operator N-ary |
| lowerLimit | java.lang.String | Batas bawah |
| upperLimit | java.lang.String | Batas atas |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instance baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Menempatkan dalam susunan vertikal

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Mengembalikan:**
[IMathArray](../../com.aspose.slides/imatharray) - Instance baru tipe [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Mengambil integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | int | Tipe integral |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas bawah integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas atas integral |
| limitLocations | int | Lokasi batas |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instance baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Mengambil integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | int | Tipe integral |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas bawah integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas atas integral |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instance baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Mengambil integral tanpa batas

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | int | Tipe integral |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instance baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Mengambil integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | int | Tipe integral |
| lowerLimit | java.lang.String | Batas bawah integral |
| upperLimit | java.lang.String | Batas atas integral |
| limitLocations | int | Lokasi batas |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instance baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Mengambil integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | int | Tipe integral |
| lowerLimit | java.lang.String | Batas bawah integral |
| upperLimit | java.lang.String | Batas atas integral |

**Mengembalikan:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instance baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Menetapkan tanda aksen (karakter di atas elemen ini)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| accentCharacter | char | Karakter aksen. Nilai harus berada dalam rentang (U+0300–U+036F) atau (U+20D0–U+20EF) |

**Mengembalikan:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Instance baru tipe [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Menetapkan bar di atas elemen ini

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Mengembalikan:**
[IMathBar](../../com.aspose.slides/imathbar) - Instance baru tipe [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Menetapkan bar di bawah elemen ini

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Mengembalikan:**
[IMathBar](../../com.aspose.slides/imathbar) - Instance baru tipe [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah

--------------------

> ```
> Contoh:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```


**Mengembalikan:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Instance baru tipe [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau karakter lain

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| character | char | Karakter Pengelompokan seperti BOTTOM CURLY BRACKET (U+23DF) atau yang lain |
| position | int | Posisi karakter pengelompokan |
| verticalJustification | int | Justifikasi vertikal karakter grup. Menentukan perataan objek terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification Top berarti bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar |

**Mengembalikan:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Instance baru tipe [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Menempatkan elemen ini dalam kotak bingkai

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Mengembalikan:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Kotak bingkai dengan elemen ini di dalamnya
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Menempatkan elemen ini dalam kotak bingkai

--------------------

> ```
> Contoh:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hideTop | boolean | Sembunyikan Tepi Atas |
| hideBottom | boolean | Sembunyikan Tepi Bawah |
| hideLeft | boolean | Sembunyikan Tepi Kiri |
| hideRight | boolean | Sembunyikan Tepi Kanan |
| strikethroughHorizontal | boolean | Garis coret Kotak Bingkai Horizontal |
| strikethroughVertical | boolean | Garis coret Kotak Bingkai Vertikal |
| strikethroughBottomLeftToTopRight | boolean | Garis coret Kotak Bingkai Dari Kiri-Bawah ke Kanan-Atas |
| strikethroughTopLeftToBottomRight | boolean | Garis coret Kotak Bingkai Dari Kiri-Atas ke Kanan-Bawah |

**Mengembalikan:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Kotak bingkai dengan elemen ini di dalamnya
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau teks matematika lainnya. Objek dalam kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik kesejajaran, berfungsi sebagai titik pemutus baris, atau dikelompokkan agar tidak mengizinkan pemutusan baris di dalamnya.

--------------------

> ```
> Contoh:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**Mengembalikan:**
[IMathBox](../../com.aspose.slides/imathbox) - Kotak logis dengan elemen ini di dalamnya
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Mendapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)