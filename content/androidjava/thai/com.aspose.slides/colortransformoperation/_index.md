---
title: ColorTransformOperation
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: กำหนดการดำเนินการแปลงสี.
type: docs
url: /th/com.aspose.slides/colortransformoperation/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

กำหนดการดำเนินการแปลงสี
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Tint](#Tint) | ทำให้สีเป็นสีอ่อน |
| [Shade](#Shade) | ทำให้สีเป็นสีเข้ม |
| [Complement](#Complement) | เปลี่ยนสีเป็นสีคอมพลีเมนท์ของ RGB |
| [Inverse](#Inverse) | เปลี่ยนสีเป็นสีตรงข้าม |
| [Grayscale](#Grayscale) | เปลี่ยนสีเป็นสีเทาที่มีความสว่างเท่าเดิม |
| [SetAlpha](#SetAlpha) | กำหนดส่วนอัลฟาของสี |
| [AddAlpha](#AddAlpha) | เพิ่มค่าพารามิเตอร์ลงในส่วนอัลฟของสี |
| [MultiplyAlpha](#MultiplyAlpha) | คูณส่วนอัลฟของสีด้วยค่าพารามิเตอร์ |
| [SetHue](#SetHue) | เปลี่ยนส่วน hue ของสีเป็นค่าพารามิเตอร์ |
| [AddHue](#AddHue) | เพิ่มค่าพารามิเตอร์ลงในส่วน hue ของสี |
| [MultiplyHue](#MultiplyHue) | คูณส่วน hue ของสีด้วยค่าพารามิเตอร์ |
| [SetSaturation](#SetSaturation) | เปลี่ยนส่วน saturation ของสีเป็นค่าพารามิเตอร์ |
| [AddSaturation](#AddSaturation) | เพิ่มค่าพารามิเตอร์ลงในส่วน saturation ของสี |
| [MultiplySaturation](#MultiplySaturation) | คูณส่วน saturation ของสีด้วยค่าพารามิเตอร์ |
| [SetLuminance](#SetLuminance) | เปลี่ยนส่วน luminance ของสีเป็นค่าพารามิเตอร์ |
| [AddLuminance](#AddLuminance) | เพิ่มค่าพารามิเตอร์ลงในส่วน luminance ของสี |
| [MultiplyLuminance](#MultiplyLuminance) | คูณส่วน luminance ของสีด้วยค่าพารามิเตอร์ |
| [SetRed](#SetRed) | เปลี่ยนส่วนสีแดงของสีเป็นค่าพารามิเตอร์ |
| [AddRed](#AddRed) | เพิ่มค่าพารามิเตอร์ลงในส่วนสีแดงของสี |
| [MultiplyRed](#MultiplyRed) | คูณส่วนสีแดงด้วยพารามิเตอร์ |
| [SetGreen](#SetGreen) | เปลี่ยนส่วนสีเขียวของสีเป็นค่าพารามิเตอร์ |
| [AddGreen](#AddGreen) | เพิ่มพารามิเตอร์ลงในส่วนสีเขียวของสี |
| [MultiplyGreen](#MultiplyGreen) | คูณส่วนสีเขียวของสีด้วยค่าพารามิเตอร์ |
| [SetBlue](#SetBlue) | เปลี่ยนส่วนสีฟ้าของสีเป็นค่าพารามิเตอร์ |
| [AddBlue](#AddBlue) | เพิ่มค่าพารามิเตอร์ลงในส่วนสีฟ้าของสี |
| [MultiplyBlue](#MultiplyBlue) | คูณส่วนสีฟ้าของสีด้วยค่าพารามิเตอร์ |
| [Gamma](#Gamma) | การแก้ไขแกมม่า |
| [InverseGamma](#InverseGamma) | การแก้ไขแกมม่าแบบย้อนกลับ |

### Tint {#Tint}
```
public static final int Tint
```

ทำให้สีอ่อนขึ้น ค่าพารามิเตอร์อยู่ในช่วงระหว่าง 0 (สีดั้งเดิม) และ 1 (สีขาว)

### Shade {#Shade}
```
public static final int Shade
```

ทำให้สีเข้มขึ้น ค่าพารามิเตอร์อยู่ในช่วงระหว่าง 0 (สีดั้งเดิม) และ 1 (สีดำ)

### Complement {#Complement}
```
public static final int Complement
```

เปลี่ยนสีเป็นสีคอมพลีเมนท์ของ RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

เปลี่ยนสีเป็นสีตรงข้าม. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

เปลี่ยนสีเป็นสีเทาที่มีความสว่างเท่าเดิม. พารามิเตอร์ถูกละเลย

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

กำหนดส่วนอัลฟของสี ค่าพารามิเตอร์อยู่ในช่วงระหว่าง 0 (โปร่งใส) และ 1 (ทึบ)

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

เพิ่มค่าพารามิเตอร์ลงในส่วนอัลฟของสี ค่าพารามิเตอร์อยู่ในช่วงระหว่าง -1 ถึง 1

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

คูณส่วนอัลฟของสีด้วยค่าพารามิเตอร์

### SetHue {#SetHue}
```
public static final int SetHue
```

เปลี่ยนส่วน hue ของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วงระหว่าง 0 ถึง 360

### AddHue {#AddHue}
```
public static final int AddHue
```

เพิ่มค่าพารามิเตอร์ลงในส่วน hue ของสี ค่าพารามิเตอร์อยู่ในช่วงระหว่าง -360 ถึง 360

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

คูณส่วน hue ของสีด้วยค่าพารามิเตอร์

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

เปลี่ยนส่วน saturation ของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วงระหว่าง 0 ถึง 1

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

เพิ่มค่าพารามิเตอร์ลงในส่วน saturation ของสี ค่าพารามิเตอร์อยู่ในช่วงระหว่าง -1 ถึง 1

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

คูณส่วน saturation ของสีด้วยค่าพารามิเตอร์

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

เปลี่ยนส่วน luminance ของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วงระหว่าง 0 ถึง 1

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

เพิ่มค่าพารามิเตอร์ลงในส่วน luminance ของสี ค่าพารามิเตอร์อยู่ในช่วงระหว่าง -1 ถึง 1

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

คูณส่วน luminance ของสีด้วยค่าพารามิเตอร์

### SetRed {#SetRed}
```
public static final int SetRed
```

เปลี่ยนส่วนสีแดงของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วงระหว่าง 0 ถึง 1

### AddRed {#AddRed}
```
public static final int AddRed
```

เพิ่มค่าพารามิเตอร์ลงในส่วนสีแดงของสี ค่าพารามิเตอร์อยู่ในช่วงระหว่าง -1 ถึง 1

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

คูณส่วนสีแดงด้วยพารามิเตอร์

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

เปลี่ยนส่วนสีเขียวของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วงระหว่าง 0 ถึง 1

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

เพิ่มพารามิเตอร์ลงในส่วนสีเขียวของสี ค่าพารามิเตอร์อยู่ในช่วงระหว่าง -1 ถึง 1

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

คูณส่วนสีเขียวของสีด้วยค่าพารามิเตอร์

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

เปลี่ยนส่วนสีฟ้าของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วงระหว่าง 0 ถึง 360

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

เพิ่มค่าพารามิเตอร์ลงในส่วนสีฟ้าของสี ค่าพารามิเตอร์อยู่ในช่วงระหว่าง -1 ถึง 1

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

คูณส่วนสีฟ้าของสีด้วยค่าพารามิเตอร์

### Gamma {#Gamma}
```
public static final int Gamma
```

การแก้ไขแกมม่า. พารามิเตอร์ถูกละเลย

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

การแก้ไขแกมม่าแบบย้อนกลับ. พารามิเตอร์ถูกละเลย