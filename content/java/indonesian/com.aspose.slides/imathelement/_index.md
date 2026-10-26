---
title: IMathElement
second_title: Aspose.Slides for Java API Reference
description: Antarmuka dasar dari setiap elemen matematika  pecahan teks matematika fungsi ekspresi dengan beberapa elemen dll
type: docs
url: /id/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Antarmuka dasar dari setiap elemen matematika: pecahan, teks matematika, fungsi, ekspresi dengan beberapa elemen dll

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getChildren()](#getChildren--) | Mendapatkan elemen anak |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [join(String mathText)](#join-java.lang.String-) | Menggabungkan teks matematika dan membentuk blok matematika |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan |
| [divide(String denominator)](#divide-java.lang.String-) | Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Membuat fraksi dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Membuat fraksi dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [enclose()](#enclose--) | Membungkus elemen matematika dalam kurung |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Membungkus elemen ini dengan karakter yang ditentukan seperti kurung atau karakter lain sebagai bingkai |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Menerima fungsi dari argumen menggunakan instance ini sebagai nama fungsi |
| [function(String functionArgument)](#function-java.lang.String-) | Menerima fungsi dari argumen menggunakan instance ini sebagai nama fungsi |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Membuat subskrip |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Membuat subskrip |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Membuat superskrip |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Membuat superskrip |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat subskrip dan superskrip di kanan |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Membuat subskrip dan superskrip di kanan |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat subskrip dan superskrip di kiri |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Membuat subskrip dan superskrip di kiri |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Menentukan akar matematika dengan derajat tertentu dari argumen yang ditentukan. |
| [radical(String degree)](#radical-java.lang.String-) | Menentukan akar matematika dengan derajat tertentu dari argumen yang ditentukan. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Mengambil batas atas |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Mengambil batas atas |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Mengambil batas bawah |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Mengambil batas bawah |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat operator N-ary |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Membuat operator N-ary |
| [toMathArray()](#toMathArray--) | Menempatkan dalam array vertikal |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Mengambil integral |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Mengambil integral |
| [integral(int integralType)](#integral-int-) | Mengambil integral tanpa batas |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Mengambil integral |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Mengambil integral |
| [accent(char accentCharacter)](#accent-char-) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [overbar()](#overbar--) | Menetapkan garis di atas elemen ini |
| [underbar()](#underbar--) | Menetapkan garis di bawah elemen ini |
| [group()](#group--) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokkan seperti kurung kurawal bawah atau lainnya |
| [toBorderBox()](#toBorderBox--) | Menempatkan elemen ini dalam kotak batas |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Menempatkan elemen ini dalam kotak batas |
| [toBox()](#toBox--) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau instansi teks matematis lainnya. |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

Mendapatkan elemen anak

**Return:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
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

**Return:**
[IMathBlock](../../com.aspose.slides/imathblock) - Blok matematika baru IMathBlock yang berisi instance ini dan argumen yang ditentukan
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
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

**Return:**
[IMathBlock](../../com.aspose.slides/imathblock) - Blok matematika baru IMathBlock yang berisi instance ini dan argumen yang ditentukan
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan

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

**Return:**
[IMathFraction](../../com.aspose.slides/imathfraction) - fraksi baru
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan

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

**Return:**
[IMathFraction](../../com.aspose.slides/imathfraction) - fraksi baru
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

Membuat fraksi dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan

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
| fractionType | int | Tipe fraksi: Bar, NoBar, Skewed, Linear |

**Return:**
[IMathFraction](../../com.aspose.slides/imathfraction) - fraksi baru
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

Membuat fraksi dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan

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
| fractionType | int | Tipe fraksi: Bar, NoBar, Skewed, Linear |

**Return:**
[IMathFraction](../../com.aspose.slides/imathfraction) - fraksi baru
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

Membungkus elemen matematika dalam kurung

--------------------

> ```
> Contoh:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Return:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Elemen matematika tipe [IMathDelimiter](../../com.aspose.slides/imathdelimiter) yang mencakup kurung
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Membungkus elemen ini dengan karakter yang ditentukan seperti kurung atau karakter lain sebagai bingkai

--------------------

> ```
> Contoh:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char | Karakter pembuka (biasanya kurung kiri) |
| endingCharacter | char | Karakter penutup (biasanya kurung kanan) |

**Return:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Elemen matematika tipe [IMathDelimiter](../../com.aspose.slides/imathdelimiter) yang mencakup karakter yang ditentukan sebagai bingkai
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

Menerima fungsi dari argumen menggunakan instance ini sebagai nama fungsi

--------------------

> ```
> Contoh:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumen fungsi |

**Return:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

Menerima fungsi dari argumen menggunakan instance ini sebagai nama fungsi

--------------------

> ```
> Contoh:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionArgument | java.lang.String | Argumen fungsi |

**Return:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen

--------------------

> ```
> Contoh:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Nama fungsi |

**Return:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen

--------------------

> ```
> Contoh:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionName | java.lang.String | Nama fungsi |

**Return:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen

--------------------

> ```
> Contoh:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | int | Salah satu tipe fungsi umum dengan satu argumen |

**Return:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan

--------------------

> ```
> Contoh:
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

**Return:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan

--------------------

> ```
> Contoh:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Mengembalikan logaritma 'x' dengan basis '5'
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | int | Salah satu tipe fungsi umum dengan dua argumen: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Argumen tambahan tergantung pada tipe fungsi |

**Return:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Elemen matematika baru tipe [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

Membuat subskrip

--------------------

> ```
> Contoh:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subskrip (indeks bawah di kanan) |

**Return:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Elemen matematika baru tipe [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

Membuat subskrip

--------------------

> ```
> Contoh:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | java.lang.String | Subskrip (indeks bawah di kanan) |

**Return:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Elemen matematika baru tipe [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
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

**Return:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Elemen matematika baru tipe [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

Membuat superskrip

--------------------

> ```
> Contoh:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| superscript | java.lang.String | Superskrip (indeks atas di kanan) |

**Return:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Elemen matematika baru tipe [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Membuat subskrip dan superskrip di kanan

--------------------

> ```
> Contoh:
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

**Return:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Elemen matematika baru tipe [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
Membuat subskrip dan superskrip di sebelah kanan

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (indeks rendah di sebelah kanan) |
| superscript | java.lang.String | Superscript (indeks atas di sebelah kanan) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Elemen matematika baru tipe [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```


Membuat subskrip dan superskrip di sebelah kiri

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (indeks rendah di sebelah kiri) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (indeks atas di sebelah kiri) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Elemen matematika baru tipe [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```


Membuat subskrip dan superskrip di sebelah kiri

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (indeks rendah di sebelah kiri) |
| superscript | java.lang.String | Superscript (indeks atas di sebelah kiri) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Elemen matematika baru tipe [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```


Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan.

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dari Radical |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - Instansi baru tipe [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```


Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan.

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| degree | java.lang.String | Argumen dari Radical |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - Instansi baru tipe [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
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

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | batas |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Instansi baru tipe [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```


Mengambil batas atas

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | java.lang.String | batas |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Instansi baru tipe [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```


Mengambil batas bawah

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | batas |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Instansi baru tipe [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```


Mengambil batas bawah

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | java.lang.String | batas |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Instansi baru tipe [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```


Membuat operator N-ary

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Tipe operator N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas bawah |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas atas |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instansi baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```


Membuat operator N-ary

--------------------

> ```
> Contoh:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Tipe operator N-ary |
| lowerLimit | java.lang.String | Batas bawah |
| upperLimit | java.lang.String | Batas atas |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instansi baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```


Menempatkan dalam array vertikal

--------------------

> ```
> Contoh:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - Instansi baru tipe [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```


Mengambil integral

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | int | Tipe integral |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas bawah integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas atas integral |
| limitLocations | int | lokasi batas |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instansi baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```


Mengambil integral

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | int | Tipe integral |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas bawah integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Batas atas integral |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instansi baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```


Mengambil integral tanpa batas

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | int | Tipe integral |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instansi baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```


Mengambil integral

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | int | Tipe integral |
| lowerLimit | java.lang.String | Batas bawah integral |
| upperLimit | java.lang.String | Batas atas integral |
| limitLocations | int | lokasi batas |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instansi baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```


Mengambil integral

--------------------

> ```
> Contoh:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | int | Tipe integral |
| lowerLimit | java.lang.String | Batas bawah integral |
| upperLimit | java.lang.String | Batas atas integral |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Instansi baru tipe [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```


Menetapkan tanda aksen (karakter di atas elemen ini)

--------------------

> ```
> Contoh:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| accentCharacter | char | Karakter aksen. Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Instansi baru tipe [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```


Menetapkan garis di atas elemen ini

--------------------

> ```
> Contoh:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - Instansi baru tipe [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```


Menetapkan garis di bawah elemen ini

--------------------

> ```
> Contoh:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - Instansi baru tipe [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```


Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah

--------------------

> ```
> Contoh:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```


**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Instansi baru tipe [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```


Menempatkan elemen ini dalam grup menggunakan karakter grup seperti kurung kurawal bawah atau lainnya

--------------------

> ```
> Contoh:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| character | char | Karakter grup seperti BOTTOM CURLY BRACKET (U+23DF) atau karakter lain |
| position | int | Posisi karakter grup |
| verticalJustification | int | Penjajaran vertikal karakter grup. Menentukan sejajar objek terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification Top menandakan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Instansi baru tipe [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```


Menempatkan elemen ini dalam border-box

--------------------

> ```
> Contoh:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box dengan elemen ini ditempatkan di dalam
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Menempatkan elemen ini dalam border-box

--------------------

> ```
> Contoh:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hideTop | boolean | Sembunyikan Tepi Atas |
| hideBottom | boolean | Sembunyikan Tepi Bawah |
| hideLeft | boolean | Sembunyikan Tepi Kiri |
| hideRight | boolean | Sembunyikan Tepi Kanan |
| strikethroughHorizontal | boolean | Garis Coret Horizontal Border Box |
| strikethroughVertical | boolean | Garis Coret Vertikal Border Box |
| strikethroughBottomLeftToTopRight | boolean | Garis Coret Bottom-Left ke Top-Right Border Box |
| strikethroughTopLeftToBottomRight | boolean | Garis Coret Top-Left ke Bottom-Right Border Box |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box dengan elemen ini ditempatkan di dalam
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```


Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau teks matematis lainnya. Sebuah objek berbentuk kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penjajaran, berfungsi sebagai titik pemisah baris, atau dikelompokkan sehingga tidak memperbolehkan pemisahan baris di dalamnya.

--------------------

> ```
> Contoh:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Returns:**
[IMathBox](../../com.aspose.slides/imathbox) - Kotak logis dengan elemen ini ditempatkan di dalam