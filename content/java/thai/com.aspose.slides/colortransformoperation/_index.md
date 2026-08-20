---
title: ColorTransformOperation
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: กำหนดการดำเนินการแปลงสี.
type: docs
url: /th/com.aspose.slides/colortransformoperation/
---
**การสืบทอด:** java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

กำหนดการดำเนินการแปลงสี
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Tint](#Tint) | ทำให้สีอ่อนขึ้น |
| [Shade](#Shade) | ทำให้สีเข้มขึ้น |
| [Complement](#Complement) | เปลี่ยนสีเป็นสีเติม RGB |
| [Inverse](#Inverse) | เปลี่ยนสีเป็นสีผกผัน |
| [Grayscale](#Grayscale) | เปลี่ยนสีเป็นสีเทาที่มีความสว่างเท่าเดิม |
| [SetAlpha](#SetAlpha) | กำหนดส่วนประกอบอัลฟาของสี |
| [AddAlpha](#AddAlpha) | เพิ่มค่าพารามิเตอร์ให้กับส่วนอัลฟาของสี |
| [MultiplyAlpha](#MultiplyAlpha) | คูณส่วนอัลฟากับค่าพารามิเตอร์ |
| [SetHue](#SetHue) | เปลี่ยนส่วนสี (hue) ของสีเป็นค่าพารามิเตอร์ |
| [AddHue](#AddHue) | เพิ่มค่าพารามิเตอร์ให้กับส่วนสี (hue) ของสี |
| [MultiplyHue](#MultiplyHue) | คูณส่วนสี (hue) กับค่าพารามิเตอร์ |
| [SetSaturation](#SetSaturation) | เปลี่ยนส่วนความอิ่มของสีเป็นค่าพารามิเตอร์ |
| [AddSaturation](#AddSaturation) | เพิ่มค่าพารามิเตอร์ให้กับส่วนความอิ่มของสี |
| [MultiplySaturation](#MultiplySaturation) | คูณส่วนความอิ่มของสีกับค่าพารามิเตอร์ |
| [SetLuminance](#SetLuminance) | เปลี่ยนส่วนความสว่างของสีเป็นค่าพารามิเตอร์ |
| [AddLuminance](#AddLuminance) | เพิ่มค่าพารามิเตอร์ให้กับส่วนความสว่างของสี |
| [MultiplyLuminance](#MultiplyLuminance) | คูณส่วนความสว่างของสีกับค่าพารามิเตอร์ |
| [SetRed](#SetRed) | เปลี่ยนส่วนสีแดงของสีเป็นค่าพารามิเตอร์ |
| [AddRed](#AddRed) | เพิ่มค่าพารามิเตอร์ให้กับส่วนสีแดงของสี |
| [MultiplyRed](#MultiplyRed) | คูณส่วนสีแดงกับพารามิเตอร์ |
| [SetGreen](#SetGreen) | เปลี่ยนส่วนสีเขียวของสีเป็นค่าพารามิเตอร์ |
| [AddGreen](#AddGreen) | เพิ่มพารามิเตอร์ให้กับส่วนสีเขียวของสี |
| [MultiplyGreen](#MultiplyGreen) | คูณส่วนสีเขียวของสีกับค่าพารามิเตอร์ |
| [SetBlue](#SetBlue) | เปลี่ยนส่วนสีน้ำเงินของสีเป็นค่าพารามิเตอร์ |
| [AddBlue](#AddBlue) | เพิ่มค่าพารามิเตอร์ให้กับส่วนสีน้ำเงินของสี |
| [MultiplyBlue](#MultiplyBlue) | คูณส่วนสีน้ำเงินของสีกับค่าพารามิเตอร์ |
| [Gamma](#Gamma) | การแก้ไขแกมม่า |
| [InverseGamma](#InverseGamma) | การแก้ไขแกมม่าแบบผกผัน |
### Tint {#Tint}
```
public static final int Tint
```

ทำให้สีอ่อนขึ้น ค่าพารามิเตอร์อยู่ในช่วง 0 (สีต้นฉบับ) ถึง 1 (สีขาว)

### Shade {#Shade}
```
public static final int Shade
```

ทำให้สีเข้มขึ้น ค่าพารามิเตอร์อยู่ในช่วง 0 (สีต้นฉบับ) ถึง 1 (สีดำ)

### Complement {#Complement}
```
public static final int Complement
```

เปลี่ยนสีเป็นสีเติม RGB m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

เปลี่ยนสีเป็นสีผกผัน r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

เปลี่ยนสีเป็นสีเทาที่มีความสว่างเท่าเดิม ค่าพารามิเตอร์ถูกละเว้น

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

กำหนดส่วนประกอบอัลฟาของสี ค่าพารามิเตอร์อยู่ในช่วง 0 (โปร่งแสง) ถึง 1 (ทึบแสง)

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

เพิ่มค่าพารามิเตอร์ให้กับส่วนอัลฟาของสี ค่าพารามิเตอร์อยู่ในช่วง -1 ถึง 1

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

คูณส่วนอัลฟากับค่าพารามิเตอร์

### SetHue {#SetHue}
```
public static final int SetHue
```

เปลี่ยนส่วนสี (hue) ของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วง 0 ถึง 360

### AddHue {#AddHue}
```
public static final int AddHue
```

เพิ่มค่าพารามิเตอร์ให้กับส่วนสี (hue) ของสี ค่าพารามิเตอร์อยู่ในช่วง -360 ถึง 360

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

คูณส่วนสี (hue) กับค่าพารามิเตอร์

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

เปลี่ยนส่วนความอิ่มของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วง 0 ถึง 1

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

เพิ่มค่าพารามิเตอร์ให้กับส่วนความอิ่มของสี ค่าพารามิเตอร์อยู่ในช่วง -1 ถึง 1

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

คูณส่วนความอิ่มของสีกับค่าพารามิเตอร์

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

เปลี่ยนส่วนความสว่างของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วง 0 ถึง 1

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

เพิ่มค่าพารามิเตอร์ให้กับส่วนความสว่างของสี ค่าพารามิเตอร์อยู่ในช่วง -1 ถึง 1

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

คูณส่วนความสว่างของสีกับค่าพารามิเตอร์

### SetRed {#SetRed}
```
public static final int SetRed
```

เปลี่ยนส่วนสีแดงของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วง 0 ถึง 1

### AddRed {#AddRed}
```
public static final int AddRed
```

เพิ่มค่าพารามิเตอร์ให้กับส่วนสีแดงของสี ค่าพารามิเตอร์อยู่ในช่วง -1 ถึง 1

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

คูณส่วนสีแดงกับพารามิเตอร์

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

เปลี่ยนส่วนสีเขียวของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วง 0 ถึง 1

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

เพิ่มพารามิเตอร์ให้กับส่วนสีเขียวของสี ค่าพารามิเตอร์อยู่ในช่วง -1 ถึง 1

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

คูณส่วนสีเขียวของสีกับค่าพารามิเตอร์

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

เปลี่ยนส่วนสีน้ำเงินของสีเป็นค่าพารามิเตอร์ ค่าพารามิเตอร์อยู่ในช่วง 0 ถึง 360

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

เพิ่มค่าพารามิเตอร์ให้กับส่วนสีน้ำเงินของสี ค่าพารามิเตอร์อยู่ในช่วง -1 ถึง 1

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

คูณส่วนสีน้ำเงินของสีกับค่าพารามิเตอร์

### Gamma {#Gamma}
```
public static final int Gamma
```

การแก้ไขแกมม่า ค่าพารามิเตอร์ถูกละเว้น

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

การแก้ไขแกมม่าแบบผกผัน ค่าพารามิเตอร์ถูกละเว้น