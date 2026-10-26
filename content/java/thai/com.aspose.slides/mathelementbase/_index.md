---
title: MathElementBase
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คลาสพื้นฐานสำหรับ IMathElement ที่มีการดำเนินการของเมธอดบางส่วนซึ่งเป็นที่ใช้ร่วมกันในคลาสที่สืบทอดทั้งหมด ใช้สำหรับการใช้งานภายในเท่านั้น.
type: docs
url: /th/com.aspose.slides/mathelementbase/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject  
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

คลาสฐานสำหรับ IMathElement พร้อมการทำงานของเมธอดบางอย่างที่เป็นสากลสำหรับคลาสทั้งหมดที่สืบทอด ใช้สำหรับการใช้งานภายในเท่านั้น คลาสที่สืบทอดต้องเป็น IMathElement.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | ส่งคืนอ็อบเจ็กต์ Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [join(String mathText)](#join-java.lang.String-) | รวมข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่กำหนด |
| [divide(String denominator)](#divide-java.lang.String-) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่กำหนด |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | สร้างเศษส่วนประเภทที่กำหนดด้วยตัวเศษนี้และตัวส่วนที่กำหนด |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | สร้างเศษส่วนประเภทที่กำหนดด้วยตัวเศษนี้และตัวส่วนที่กำหนด |
| [enclose()](#enclose--) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [function(String functionArgument)](#function-java.lang.String-) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และรับอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และรับอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | สร้างตัวห้อย |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | สร้างตัวห้อย |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | สร้างตัวบน |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | สร้างตัวบน |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างตัวห้อยและตัวบนทางด้านขวา |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | สร้างตัวห้อยและตัวบนทางด้านขวา |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างตัวห้อยและตัวบนทางด้านซ้าย |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | สร้างตัวห้อยและตัวบนทางด้านซ้าย |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [radical(String degree)](#radical-java.lang.String-) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | รับค่าขอบบน |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | รับค่าขอบบน |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | รับค่าขอบล่าง |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | รับค่าขอบล่าง |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างตัวดำเนินการ N-ary |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | สร้างตัวดำเนินการ N-ary |
| [toMathArray()](#toMathArray--) | ใส่ในอาเรย์แนวตั้ง |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | รับอินทิกรัล |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | รับอินทิกรัล |
| [integral(int integralType)](#integral-int-) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | รับอินทิกรัล |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | รับอินทิกรัล |
| [accent(char accentCharacter)](#accent-char-) | ตั้งเครื่องหมายสำเนียง (อักขระด้านบนขององค์ประกอบนี้) |
| [overbar()](#overbar--) | ตั้งบาร์บนด้านบนขององค์ประกอบนี้ |
| [underbar()](#underbar--) | ตั้งบาร์ด้านล่างขององค์ประกอบนี้ |
| [group()](#group--) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น วงเล็บโค้งล่างหรืออักขระอื่น |
| [toBorderBox()](#toBorderBox--) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [toBox()](#toBox--) | ใส่องค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น |
| [getChildren()](#getChildren--) | รับองค์ประกอบลูก |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ผลลัพธ์:**  
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบที่จะถูกรวม |

**ผลลัพธ์:**  
[IMathBlock](../../com.aspose.slides/imathblock) - IMathBlock ใหม่ที่มีอินสแตนซ์นี้และอาร์กิวเมนต์ที่ระบุ

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

รวมข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | java.lang.String | ข้อความคณิตศาสตร์ที่จะถูกรวม |

**ผลลัพธ์:**  
[IMathBlock](../../com.aspose.slides/imathblock) - IMathBlock ใหม่ที่มีอินสแตนซ์นี้และอาร์กิวเมนต์ที่ระบุ

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่กำหนด

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวส่วน |

**ผลลัพธ์:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษส่วนใหม่

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่กำหนด

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | java.lang.String | ตัวส่วน |

**ผลลัพธ์:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษส่วนใหม่

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

สร้างเศษส่วนประเภทที่กำหนดด้วยตัวเศษนี้และตัวส่วนที่กำหนด

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวส่วน |
| fractionType | int | ประเภทของเศษส่วน: Bar, NoBar, Skewed, Linear |

**ผลลัพธ์:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษส่วนใหม่

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

สร้างเศษส่วนประเภทที่กำหนดด้วยตัวเศษนี้และตัวส่วนที่กำหนด

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | java.lang.String | ตัวส่วน |
| fractionType | int | ประเภทของเศษส่วน: Bar, NoBar, Skewed, Linear |

**ผลลัพธ์:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษส่วนใหม่

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**ผลลัพธ์:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../com.aspose.slides/imathdelimiter) ซึ่งรวมวงเล็บ

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char | อักขระเริ่มต้น (โดยทั่วไปเป็นวงเล็บซ้าย) |
| endingCharacter | char | อักขระสิ้นสุด (โดยทั่วไปเป็นวงเล็บขวา) |

**ผลลัพธ์:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../com.aspose.slides/imathdelimiter) ซึ่งรวมอักขระที่ระบุเป็นกรอบ

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ของฟังก์ชัน |

**ผลลัพธ์:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionArgument | java.lang.String | อาร์กิวเมนต์ของฟังก์ชัน |

**ผลลัพธ์:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | ชื่อฟังก์ชัน |

**ผลลัพธ์:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionName | java.lang.String | ชื่อฟังก์ชัน |

**ผลลัพธ์:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionType | int | หนึ่งในประเภทฟังก์ชันที่ใช้กับอาร์กิวเมนต์หนึ่ง |

**ผลลัพธ์:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และรับอาร์กิวเมนต์เพิ่มเติมที่ระบุ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // คืนค่าลอการิทึมของ 'x' ไปยังฐาน '5'
```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionType | int | หนึ่งในประเภทฟังก์ชันที่ใช้กับอาร์กิวเมนต์สอง: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์เพิ่มเติมขึ้นกับประเภทของฟังก์ชัน |

**ผลลัพธ์:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และรับอาร์กิวเมนต์เพิ่มเติมที่ระบุ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // คืนค่าลอการิทึมของ 'x' ไปยังฐาน '5'
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionType | int | หนึ่งในประเภทฟังก์ชันที่ใช้กับอาร์กิวเมนต์สอง: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | อาร์กิวเมนต์เพิ่มเติมขึ้นกับประเภทของฟังก์ชัน |

**ผลลัพธ์:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

สร้างตัวห้อย

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | ตัวห้อย (ดัชนีล่างด้านขวา) |

**ผลลัพธ์:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

สร้างตัวห้อย

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | java.lang.String | ตัวห้อย (ดัชนีล่างด้านขวา) |

**ผลลัพธ์:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

สร้างตัวบน

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | ตัวบน (ดัชนีบนด้านขวา) |

**ผลลัพธ์:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

สร้างตัวบน

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| superscript | java.lang.String | ตัวบน (ดัชนีบนด้านขวา) |

**ผลลัพธ์:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

สร้างตัวห้อยและตัวบนทางด้านขวา

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | ตัวห้อย (ดัชนีล่างด้านขวา) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | ตัวบน (ดัชนีบนด้านขวา) |

**ผลลัพธ์:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

สร้างตัวห้อยและตัวบนทางด้านขวา
> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| subscript | java.lang.String | ตัวห้อย (ดัชนีล่างทางขวา) |
| superscript | java.lang.String | ตัวสูง (ดัชนีบนทางขวา) |

**ผลลัพธ์:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

สร้างตัวห้อยและตัวสูงทางซ้าย

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | ตัวห้อย (ดัชนีล่างทางซ้าย) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | ตัวสูง (ดัชนีบนทางซ้าย) |

**ผลลัพธ์:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

สร้างตัวห้อยและตัวสูงทางซ้าย

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| subscript | java.lang.String | ตัวห้อย (ดัชนีล่างทางซ้าย) |
| superscript | java.lang.String | ตัวสูง (ดัชนีบนทางซ้าย) |

**ผลลัพธ์:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ของรากคณิตศาสตร์ |

**ผลลัพธ์:**
[IMathRadical](../../com.aspose.slides/imathradical) - อินสแตนซ์ใหม่ประเภท [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| degree | java.lang.String | อาร์กิวเมนต์ของรากคณิตศาสตร์ |

**ผลลัพธ์:**
[IMathRadical](../../com.aspose.slides/imathradical) - อินสแตนซ์ใหม่ประเภท [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

รับขอบบน

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**ผลลัพธ์:**
[IMathLimit](../../com.aspose.slides/imathlimit) - อินสแตนซ์ใหม่ประเภท [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

รับขอบบน

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| limit | java.lang.String | limit |

**ผลลัพธ์:**
[IMathLimit](../../com.aspose.slides/imathlimit) - อินสแตนซ์ใหม่ประเภท [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

รับขอบล่าง

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**ผลลัพธ์:**
[IMathLimit](../../com.aspose.slides/imathlimit) - อินสแตนซ์ใหม่ประเภท [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

รับขอบล่าง

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| limit | java.lang.String | limit |

**ผลลัพธ์:**
[IMathLimit](../../com.aspose.slides/imathlimit) - อินสแตนซ์ใหม่ประเภท [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

สร้างตัวดำเนินการ N-ary

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของตัวดำเนินการ N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่าง |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบบน |

**ผลลัพธ์:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

สร้างตัวดำเนินการ N-ary

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของตัวดำเนินการ N-ary |
| lowerLimit | java.lang.String | ขอบล่าง |
| upperLimit | java.lang.String | ขอบบน |

**ผลลัพธ์:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

ใส่ในอาร์เรย์แนวตั้ง

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**ผลลัพธ์:**
[IMathArray](../../com.aspose.slides/imatharray) - อินสแตนซ์ใหม่ประเภท [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

รับอินทิกรัล

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| integralType | int | ประเภทของอินทิกรัล |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่างของอินทิกรัล |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบบนของอินทิกรัล |
| limitLocations | int | ตำแหน่งของขอบ |

**ผลลัพธ์:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

รับอินทิกรัล

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| integralType | int | ประเภทของอินทิกรัล |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่างของอินทิกรัล |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบบนของอินทิกรัล |

**ผลลัพธ์:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

รับอินทิกรัลโดยไม่มีขอบ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| integralType | int | ประเภทของอินทิกรัล |

**ผลลัพธ์:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

รับอินทิกรัล

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| integralType | int | ประเภทของอินทิกรัล |
| lowerLimit | java.lang.String | ขอบล่างของอินทิกรัล |
| upperLimit | java.lang.String | ขอบบนของอินทิกรัล |
| limitLocations | int | ตำแหน่งของขอบ |

**ผลลัพธ์:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

รับอินทิกรัล

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| integralType | int | ประเภทของอินทิกรัล |
| lowerLimit | java.lang.String | ขอบล่างของอินทิกรัล |
| upperLimit | java.lang.String | ขอบบนของอินทิกรัล |

**ผลลัพธ์:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

ตั้งเครื่องหมายสำเนียง (อักขระบนสุดของส่วนนี้)

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| accentCharacter | char | ตัวอักขระสำเนียง ค่าควรอยู่ในช่วง (U+0300\u2013U+036F) หรือ (U+20D0\u2013U+20EF) |

**ผลลัพธ์:**
[IMathAccent](../../com.aspose.slides/imathaccent) - อินสแตนซ์ใหม่ประเภท [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

ตั้งแถบบนของส่วนนี้

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**ผลลัพธ์:**
[IMathBar](../../com.aspose.slides/imathbar) - อินสแตนซ์ใหม่ประเภท [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

ตั้งแถบล่างของส่วนนี้

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**ผลลัพธ์:**
[IMathBar](../../com.aspose.slides/imathbar) - อินสแตนซ์ใหม่ประเภท [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

วางส่วนนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**ผลลัพธ์:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - อินสแตนซ์ใหม่ประเภท [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

วางส่วนนี้ในกลุ่มโดยใช้อักขระกลุ่มเช่นวงเล็บปีกกาล่างหรืออักขระอื่น

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| character | char | อักขระกลุ่มเช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่นใด |
| position | int | ตำแหน่งของอักขระกลุ่ม |
| verticalJustification | int | การจัดแนวแนวตั้งของอักขระกลุ่ม ระบุการจัดแนวของวัตถุตามเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถุ การจัดแนวแนวตั้ง Top หมายถึงด้านบนของวัตถุอยู่บนเส้นฐาน; เมื่อกำหนดเป็น Bottom ด้านล่างของวัตถุอยู่บนเส้นฐาน |

**ผลลัพธ์:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - อินสแตนซ์ใหม่ประเภท [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

วางส่วนนี้ใน border-box

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**ผลลัพธ์:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box ที่มีส่วนนี้อยู่ภายใน
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

วางส่วนนี้ใน border-box

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hideTop | boolean | ซ่อนขอบบน |
| hideBottom | boolean | ซ่อนขอบล่าง |
| hideLeft | boolean | ซ่อนขอบซ้าย |
| hideRight | boolean | ซ่อนขอบขวา |
| strikethroughHorizontal | boolean | เส้นขีดกรอบแนวนอน |
| strikethroughVertical | boolean | เส้นขีดกรอบแนวตั้ง |
| strikethroughBottomLeftToTopRight | boolean | เส้นขีดกรอบจากล่างซ้ายไปบนขวา |
| strikethroughTopLeftToBottomRight | boolean | เส้นขีดกรอบจากบนซ้ายไปล่างขวา |

**ผลลัพธ์:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box ที่มีส่วนนี้อยู่ภายใน
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

วางส่วนนี้ในกล่องที่ไม่แสดงผล (กลุ่มตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่อยู่ในกล่องอาจทำหน้าที่เป็นตัวจำลองตัวดำเนินการพร้อมหรือไม่มีจุดจัดตำแหน่ง ใช้เป็นจุดตัดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**ผลลัพธ์:**
[IMathBox](../../com.aspose.slides/imathbox) - กล่องตรรกะที่มีส่วนนี้อยู่ภายใน
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

รับส่วนย่อย

**ผลลัพธ์:**
com.aspose.slides.IMathElement[] - อาร์เรย์ของ [IMathElement](../../com.aspose.slides/imathelement)