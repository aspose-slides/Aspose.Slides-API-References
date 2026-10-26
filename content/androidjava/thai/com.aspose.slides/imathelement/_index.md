---
title: IMathElement
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อินเทอร์เฟซฐานขององค์ประกอบคณิตศาสตร์ใด ๆ: เศษส่วน, ข้อความคณิตศาสตร์, ฟังก์ชัน, นิพจน์ที่มีหลายองค์ประกอบ ฯลฯ
type: docs
url: /th/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

อินเทอร์เฟซฐานขององค์ประกอบคณิตศาสตร์ใด ๆ: เศษส่วน, ข้อความคณิตศาสตร์, ฟังก์ชัน, นิพจน์ที่มีหลายองค์ประกอบ ฯลฯ

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChildren()](#getChildren--) | รับองค์ประกอบย่อย |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [join(String mathText)](#join-java.lang.String-) | รวมข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวหารที่ระบุ |
| [divide(String denominator)](#divide-java.lang.String-) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวหารที่ระบุ |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวหารที่ระบุ |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวหารที่ระบุ |
| [enclose()](#enclose--) | ใส่วงเล็บรอบองค์ประกอบคณิตศาสตร์ |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | ใส่วงเล็บหรืออักขระอื่น ๆ รอบองค์ประกอบนี้เป็นกรอบ |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [function(String functionArgument)](#function-java.lang.String-) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | สร้างสคริปต์ย่อย |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | สร้างสคริปต์ย่อย |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | สร้างสคริปต์ยกกำลัง |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | สร้างสคริปต์ยกกำลัง |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างสคริปต์ย่อยและสคริปต์ยกกำลังทางขวา |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | สร้างสคริปต์ย่อยและสคริปต์ยกกำลังทางขวา |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างสคริปต์ย่อยและสคริปต์ยกกำลังทางซ้าย |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | สร้างสคริปต์ย่อยและสคริปต์ยกกำลังทางซ้าย |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [radical(String degree)](#radical-java.lang.String-) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | รับค่าขีดจำกัดบน |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | รับค่าขีดจำกัดบน |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | รับค่าขีดจำกัดล่าง |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | รับค่าขีดจำกัดล่าง |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างตัวดำเนินการ N-ary |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | สร้างตัวดำเนินการ N-ary |
| [toMathArray()](#toMathArray--) | ใส่ในอาร์เรย์แนวตั้ง |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | รับอินทิกรัล |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | รับอินทิกรัล |
| [integral(int integralType)](#integral-int-) | รับอินทิกรัลโดยไม่มีขีดจำกัด |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | รับอินทิกรัล |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | รับอินทิกรัล |
| [accent(char accentCharacter)](#accent-char-) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [overbar()](#overbar--) | ตั้งแถบบนสุดขององค์ประกอบนี้ |
| [underbar()](#underbar--) | ตั้งแถบล่างขององค์ประกอบนี้ |
| [group()](#group--) | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรการจัดกลุ่มเช่นวงเล็บโค้งล่างหรืออักขระอื่น |
| [toBorderBox()](#toBorderBox--) | วางองค์ประกอบนี้ในกล่องกรอบ |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | วางองค์ประกอบนี้ในกล่องกรอบ |
| [toBox()](#toBox--) | วางองค์ประกอบนี้ในกล่องไม่มีการแสดงผล (การจัดกลุ่มเชิงตรรกะ) ที่ใช้จัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

รับองค์ประกอบย่อย

**คืนค่า:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบที่ต้องการรวม |

**คืนค่า:**
[IMathBlock](../../com.aspose.slides/imathblock) - IMathBlock ใหม่ที่มีอินสแตนซ์นี้และอาร์กิวเมนต์ที่ระบุ
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
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
| mathText | java.lang.String | ข้อความคณิตศาสตร์ที่ต้องการรวม |

**คืนค่า:**
[IMathBlock](../../com.aspose.slides/imathblock) - IMathBlock ใหม่ที่มีอินสแตนซ์นี้และอาร์กิวเมนต์ที่ระบุ
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

สร้างเศษส่วนด้วยตัวเศษนี้และตัวหารที่ระบุ

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
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวหาร |

**คืนค่า:**
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษส่วนใหม่
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

สร้างเศษส่วนด้วยตัวเศษนี้และตัวหารที่ระบุ

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
| denominator | java.lang.String | ตัวหาร |

**คืนค่า:**
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษส่วนใหม่
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวหารที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวหาร |
| fractionType | int | ประเภทของเศษส่วน: Bar, NoBar, Skewed, Linear |

**คืนค่า:**
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษส่วนใหม่
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวหารที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | java.lang.String | ตัวหาร |
| fractionType | int | ประเภทของเศษส่วน: Bar, NoBar, Skewed, Linear |

**คืนค่า:**
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษส่วนใหม่
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

ใส่วงเล็บรอบองค์ประกอบคณิตศาสตร์

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**คืนค่า:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../com.aspose.slides/imathdelimiter) ซึ่งรวมวงเล็บไว้
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

ใส่วงเล็บหรืออักขระอื่น ๆ รอบองค์ประกอบนี้เป็นกรอบ

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
| beginningCharacter | char | อักขระเริ่มต้น (โดยทั่วไปคือวงเล็บซ้าย) |
| endingCharacter | char | อักขระสิ้นสุด (โดยทั่วไปคือวงเล็บขวา) |

**คืนค่า:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../com.aspose.slides/imathdelimiter) ซึ่งรวมอักขระที่ระบุเป็นกรอบ
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ของฟังก์ชัน |

**คืนค่า:**
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionArgument | java.lang.String | อาร์กิวเมนต์ของฟังก์ชัน |

**คืนค่า:**
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | ชื่อฟังก์ชัน |

**คืนค่า:**
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionName | java.lang.String | ชื่อฟังก์ชัน |

**คืนค่า:**
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionType | int | หนึ่งในประเภทฟังก์ชันที่ใช้กับอาร์กิวเมนต์เดียว |

**คืนค่า:**
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // คืนค่าลอการิทึมของ 'x' ไปยังฐาน '5'
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionType | int | หนึ่งในประเภทฟังก์ชันที่ใช้กับสองอาร์กิวเมนต์: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์เพิ่มเติมตามประเภทของฟังก์ชัน |

**คืนค่า:**
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // คืนค่าลอการิทึมของ 'x' ไปยังฐาน '5'
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionType | int | หนึ่งในประเภทฟังก์ชันที่ใช้กับสองอาร์กิวเมนต์: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | อาร์กิวเมนต์เพิ่มเติมตามประเภทของฟังก์ชัน |

**คืนค่า:**
[IMathFunction](../../com.aspose.slides/imathfunction) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

สร้างสคริปต์ย่อย

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | สคริปต์ย่อย (ดัชนีล่างด้านขวา) |

**คืนค่า:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

สร้างสคริปต์ย่อย

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | java.lang.String | สคริปต์ย่อย (ดัชนีล่างด้านขวา) |

**คืนค่า:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

สร้างสคริปต์ยกกำลัง

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | สคริปต์ยกกำลัง (ดัชนีบนด้านขวา) |

**คืนค่า:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

สร้างสคริปต์ยกกำลัง

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| superscript | java.lang.String | สคริปต์ยกกำลัง (ดัชนีบนด้านขวา) |

**คืนค่า:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

สร้างสคริปต์ย่อยและสคริปต์ยกกำลังทางขวา

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | สคริปต์ย่อย (ดัชนีล่างด้านขวา) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | สคริปต์ยกกำลัง (ดัชนีบนด้านขวา) |

**คืนค่า:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

สร้างสคริปต์ย่อยและสคริปต์ยกกำลังทางขวา

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | java.lang.String | สคริปต์ย่อย (ดัชนีล่างด้านซ้าย) |
| superscript | java.lang.String | สคริปต์ยกกำลัง (ดัชนีบนด้านซ้าย) |

**คืนค่า:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

สร้างสคริปต์ย่อยและสคริปต์ยกกำลังทางซ้าย

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | สคริปต์ย่อย (ดัชนีล่างด้านซ้าย) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | สคริปต์ยกกำลัง (ดัชนีบนด้านซ้าย) |

**คืนค่า:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

สร้างสคริปต์ย่อยและสคริปต์ยกกำลังทางซ้าย

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | java.lang.String | สคริปต์ย่อย (ดัชนีล่างด้านซ้าย) |
| superscript | java.lang.String | สคริปต์ยกกำลัง (ดัชนีบนด้านซ้าย) |

**คืนค่า:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ของรากกำลัง |

**คืนค่า:**
[IMathRadical](../../com.aspose.slides/imathradical) - อินสแตนซ์ใหม่ประเภท [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| degree | java.lang.String | อาร์กิวเมนต์ของรากกำลัง |

**คืนค่า:**
[IMathRadical](../../com.aspose.slides/imathradical) - อินสแตนซ์ใหม่ประเภท [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

รับค่าขีดจำกัดบน

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | ค่าขีดจำกัด |

**คืนค่า:**
[IMathLimit](../../com.aspose.slides/imathlimit) - อินสแตนซ์ใหม่ประเภท [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

รับค่าขีดจำกัดบน

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| limit | java.lang.String | ค่าขีดจำกัด |

**คืนค่า:**
[IMathLimit](../../com.aspose.slides/imathlimit) - อินสแตนซ์ใหม่ประเภท [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

รับค่าขีดจำกัดล่าง

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | ค่าขีดจำกัด |

**คืนค่า:**
[IMathLimit](../../com.aspose.slides/imathlimit) - อินสแตนซ์ใหม่ประเภท [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

รับค่าขีดจำกัดล่าง

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| limit | java.lang.String | ค่าขีดจำกัด |

**คืนค่า:**
[IMathLimit](../../com.aspose.slides/imathlimit) - อินสแตนซ์ใหม่ประเภท [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

สร้างตัวดำเนินการ N-ary

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของตัวดำเนินการ N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ค่าขีดจำกัดล่าง |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ค่าขีดจำกัดบน |

**คืนค่า:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

สร้างตัวดำเนินการ N-ary

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของตัวดำเนินการ N-ary |
| lowerLimit | java.lang.String | ค่าขีดจำกัดล่าง |
| upperLimit | java.lang.String | ค่าขีดจำกัดบน |

**คืนค่า:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

ใส่ในอาร์เรย์แนวตั้ง

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**คืนค่า:**
[IMathArray](../../com.aspose.slides/imatharray) - อินสแตนซ์ใหม่ประเภท [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| integralType | int | ประเภทของอินทิกรัล |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ค่าขีดจำกัดล่างของอินทิกรัล |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ค่าขีดจำกัดบนของอินทิกรัล |
| limitLocations | int | ตำแหน่งของขีดจำกัด |

**คืนค่า:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| integralType | int | ประเภทของอินทิกรัล |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ค่าขีดจำกัดล่างของอินทิกรัล |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ค่าขีดจำกัดบนของอินทิกรัล |

**คืนค่า:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

รับอินทิกรัลโดยไม่มีขีดจำกัด

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| integralType | int | ประเภทของอินทิกรัล |

**คืนค่า:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

รับอินทิกรัล

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| integralType | int | ประเภทของอินทิกรัล |
| lowerLimit | java.lang.String | ค่าขีดจำกัดล่างของอินทิกรัล |
| upperLimit | java.lang.String | ค่าขีดจำกัดบนของอินทิกรัล |
| limitLocations | int | ตำแหน่งของขีดจำกัด |

**คืนค่า:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| integralType | int | ประเภทของอินทิกรัล |
| lowerLimit | java.lang.String | ค่าขีดจำกัดล่างของอินทิกรัล |
| upperLimit | java.lang.String | ค่าขีดจำกัดบนของอินทิกรัล |

**คืนค่า:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - อินสแตนซ์ใหม่ประเภท [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| accentCharacter | char | ตัวอักขระสำเนียง ค่าต้องอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) |

**คืนค่า:**
[IMathAccent](../../com.aspose.slides/imathaccent) - อินสแตนซ์ใหม่ประเภท [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

ตั้งแถบบนสุดขององค์ประกอบนี้

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**คืนค่า:**
[IMathBar](../../com.aspose.slides/imathbar) - อินสแตนซ์ใหม่ประเภท [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

ตั้งแถบล่างขององค์ประกอบนี้

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**คืนค่า:**
[IMathBar](../../com.aspose.slides/imathbar) - อินสแตนซ์ใหม่ประเภท [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**คืนค่า:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - อินสแตนซ์ใหม่ประเภท [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรการจัดกลุ่มเช่นวงเล็บโค้งล่างหรืออักขระอื่น

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| character | char | ตัวอักษรการจัดกลุ่มเช่น BOTTOM CURLY BRACKET (U+23DF) หรืออักขระอื่น |
| position | int | ตำแหน่งของตัวอักษรการจัดกลุ่ม |
| verticalJustification | int | การจัดแนวตั้งของตัวอักษรการจัดกลุ่ม ระบุการจัดตำแหน่งของวัตถุตาม baseline ตัวอย่าง เมื่อตัวอักษรกลุ่มอยู่เหนือวัตถุ VerticalJustification ของ Top หมายถึงด้านบนของวัตถุตกที่ baseline; เมื่อตั้งเป็น Bottom ด้านล่างของวัตถุตกที่ baseline |

**คืนค่า:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - อินสแตนซ์ใหม่ประเภท [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

วางองค์ประกอบนี้ในกล่องกรอบ

--------------------

> ```
public abstract IMathBorderBox toBorderBox()
```

**คืนค่า:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - กล่องกรอบที่มีองค์ประกอบนี้อยู่ภายใน
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

วางองค์ประกอบนี้ในกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hideTop | boolean | ซ่อนขอบบน |
| hideBottom | boolean | ซ่อนขอบล่าง |
| hideLeft | boolean | ซ่อนขอบซ้าย |
| hideRight | boolean | ซ่อนขอบขวา |
| strikethroughHorizontal | boolean | เส้นขีดทับแนวนอนของกล่องกรอบ |
| strikethroughVertical | boolean | เส้นขีดทับแนวตั้งของกล่องกรอบ |
| strikethroughBottomLeftToTopRight | boolean | เส้นขีดทับจากซ้ายล่างไปขวาบน |
| strikethroughTopLeftToBottomRight | boolean | เส้นขีดทับจากซ้ายบนไปขวาล่าง |

**คืนค่า:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - กล่องกรอบที่มีองค์ประกอบนี้อยู่ภายใน
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

วางองค์ประกอบนี้ในกล่องไม่มีการแสดงผล (การจัดกลุ่มเชิงตรรกะ) ที่ใช้จัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุในกล่องสามารถทำหน้าที่เป็นอีมูเลเตอร์ของตัวดำเนินการที่มีหรือไม่มีจุดจัดแนว ใช้เป็นจุดแบ่งบรรทัด หรือจัดกลุ่มเพื่อไม่ให้เกิดการตัดบรรทัดภายใน

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**คืนค่า:**
[IMathBox](../../com.aspose.slides/imathbox) - กล่องเชิงตรรกะที่มีองค์ประกอบนี้อยู่ภายใน