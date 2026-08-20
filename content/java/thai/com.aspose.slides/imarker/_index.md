---
title: IMarker
second_title: Aspose.Slides for Java API Reference
description: แสดงถึงมาร์กเกอร์ของแผนภูมิ
type: docs
url: /th/com.aspose.slides/imarker/
---```
public interface IMarker
```

แสดงถึงมาร์กเกอร์ของแผนภูมิ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSymbol()](#getSymbol--) | แสดงถึงสไตล์มาร์กเกอร์ในแผนภูมิเส้น, แผนภูมิกระจาย, หรือแผนภูมิดาว |
| [setSymbol(int value)](#setSymbol-int-) | แสดงถึงสไตล์มาร์กเกอร์ในแผนภูมิเส้น, แผนภูมิกระจาย, หรือแผนภูมิดาว |
| [getFormat()](#getFormat--) | รับค่าเติมของมาร์กเกอร์ |
| [getSize()](#getSize--) | แสดงถึงขนาดมาร์กเกอร์ในแผนภูมิเส้น, แผนภูมิกระจาย, หรือแผนภูมิดาว |
| [setSize(int value)](#setSize-int-) | แสดงถึงขนาดมาร์กเกอร์ในแผนภูมิเส้น, แผนภูมิกระจาย, หรือแผนภูมิดาว |
### getSymbol() {#getSymbol--}
```
public abstract int getSymbol()
```

แสดงถึงสไตล์มาร์กเกอร์ในแผนภูมิเส้น, แผนภูมิกระจาย, หรือแผนภูมิดาว. อ่าน/เขียน [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**คืนค่า:**
int
### setSymbol(int value) {#setSymbol-int-}
```
public abstract void setSymbol(int value)
```

แสดงถึงสไตล์มาร์กเกอร์ในแผนภูมิเส้น, แผนภูมิกระจาย, หรือแผนภูมิดาว. อ่าน/เขียน [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

รับค่าเติมของมาร์กเกอร์. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### getSize() {#getSize--}
```
public abstract int getSize()
```

แสดงถึงขนาดมาร์กเกอร์ในแผนภูมิเส้น, แผนภูมิกระจาย, หรือแผนภูมิดาว. อ่าน/เขียน int.

**คืนค่า:**
int
### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```

แสดงถึงขนาดมาร์กเกอร์ในแผนภูมิเส้น, แผนภูมิกระจาย, หรือแผนภูมิดาว. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |