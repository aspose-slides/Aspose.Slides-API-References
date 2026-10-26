---
title: ColorTransformOperation
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định thao tác biến đổi màu.
type: docs
url: /vi/com.aspose.slides/colortransformoperation/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Xác định thao tác biến đổi màu.

## Trường

| Trường | Mô tả |
| --- | --- |
| [Tint](#Tint) | Tô màu. |
| [Shade](#Shade) | Tạo bóng cho màu. |
| [Complement](#Complement) | Thay đổi màu thành một màu bổ sung RGB. |
| [Inverse](#Inverse) | Thay đổi màu thành màu đảo ngược. |
| [Grayscale](#Grayscale) | Thay đổi màu thành màu xám với độ sáng giống nhau. |
| [SetAlpha](#SetAlpha) | Xác định thành phần alpha của màu. |
| [AddAlpha](#AddAlpha) | Thêm giá trị của tham số vào thành phần alpha của màu. |
| [MultiplyAlpha](#MultiplyAlpha) | Nhân thành phần alpha với giá trị của tham số. |
| [SetHue](#SetHue) | Thay đổi thành phần hue của màu thành giá trị của tham số. |
| [AddHue](#AddHue) | Thêm giá trị của tham số vào thành phần hue của màu. |
| [MultiplyHue](#MultiplyHue) | Nhân thành phần hue với giá trị của tham số. |
| [SetSaturation](#SetSaturation) | Thay đổi thành phần saturation của màu thành giá trị của tham số. |
| [AddSaturation](#AddSaturation) | Thêm giá trị của tham số vào thành phần saturation của màu. |
| [MultiplySaturation](#MultiplySaturation) | Nhân thành phần saturation với giá trị của tham số. |
| [SetLuminance](#SetLuminance) | Thay đổi thành phần luminance của màu thành giá trị của tham số. |
| [AddLuminance](#AddLuminance) | Thêm giá trị của tham số vào thành phần luminance của màu. |
| [MultiplyLuminance](#MultiplyLuminance) | Nhân thành phần luminance với giá trị của tham số. |
| [SetRed](#SetRed) | Thay đổi thành phần đỏ của màu thành giá trị của tham số. |
| [AddRed](#AddRed) | Thêm giá trị của tham số vào thành phần đỏ của màu. |
| [MultiplyRed](#MultiplyRed) | Nhân thành phần đỏ với tham số. |
| [SetGreen](#SetGreen) | Thay đổi thành phần xanh lá của màu thành giá trị của tham số. |
| [AddGreen](#AddGreen) | Thêm một tham số vào thành phần xanh lá của màu. |
| [MultiplyGreen](#MultiplyGreen) | Nhân thành phần xanh lá của màu với giá trị của tham số. |
| [SetBlue](#SetBlue) | Thay đổi thành phần xanh dương của màu thành giá trị của tham số. |
| [AddBlue](#AddBlue) | Thêm giá trị của tham số vào thành phần xanh dương của màu. |
| [MultiplyBlue](#MultiplyBlue) | Nhân thành phần xanh dương với giá trị của tham số. |
| [Gamma](#Gamma) | Điều chỉnh gamma. |
| [InverseGamma](#InverseGamma) | Điều chỉnh gamma ngược. |

### Tint {#Tint}
```
public static final int Tint
```

Tô màu. Tham số nằm trong khoảng từ 0 (màu gốc) đến 1 (trắng).

### Shade {#Shade}
```
public static final int Shade
```

Tạo bóng cho màu. Tham số nằm trong khoảng từ 0 (màu gốc) đến 1 (đen).

### Complement {#Complement}
```
public static final int Complement
```

Thay đổi màu thành một màu bổ sung RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Thay đổi màu thành màu đảo ngược. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Thay đổi màu thành màu xám với độ sáng giống nhau. Tham số bị bỏ qua.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Xác định thành phần alpha của màu. Tham số nằm trong khoảng từ 0 (trong suốt) đến 1 (đục).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Thêm giá trị của tham số vào thành phần alpha của màu. Tham số nằm trong khoảng từ -1 đến 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Nhân thành phần alpha với giá trị của tham số.

### SetHue {#SetHue}
```
public static final int SetHue
```

Thay đổi thành phần hue của màu thành giá trị của tham số. Tham số nằm trong khoảng từ 0 đến 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Thêm giá trị của tham số vào thành phần hue của màu. Tham số nằm trong khoảng từ -360 đến 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Nhân thành phần hue với giá trị của tham số.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Thay đổi thành phần saturation của màu thành giá trị của tham số. Tham số nằm trong khoảng từ 0 đến 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Thêm giá trị của tham số vào thành phần saturation của màu. Tham số nằm trong khoảng từ -1 đến 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Nhân thành phần saturation với giá trị của tham số.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Thay đổi thành phần luminance của màu thành giá trị của tham số. Tham số nằm trong khoảng từ 0 đến 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Thêm giá trị của tham số vào thành phần luminance của màu. Tham số nằm trong khoảng từ -1 đến 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Nhân thành phần luminance với giá trị của tham số.

### SetRed {#SetRed}
```
public static final int SetRed
```

Thay đổi thành phần đỏ của màu thành giá trị của tham số. Tham số nằm trong khoảng từ 0 đến 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Thêm giá trị của tham số vào thành phần đỏ của màu. Tham số nằm trong khoảng từ -1 đến 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Nhân thành phần đỏ với tham số.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Thay đổi thành phần xanh lá của màu thành giá trị của tham số. Tham số nằm trong khoảng từ 0 đến 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Thêm một tham số vào thành phần xanh lá của màu. Tham số nằm trong khoảng từ -1 đến 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Nhân thành phần xanh lá của màu với giá trị của tham số.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Thay đổi thành phần xanh dương của màu thành giá trị của tham số. Tham số nằm trong khoảng từ 0 đến 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Thêm giá trị của tham số vào thành phần xanh dương của màu. Tham số nằm trong khoảng từ -1 đến 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Nhân thành phần xanh dương với giá trị của tham số.

### Gamma {#Gamma}
```
public static final int Gamma
```

Điều chỉnh gamma. Tham số bị bỏ qua.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Điều chỉnh gamma ngược. Tham số bị bỏ qua.