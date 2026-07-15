---
title: ColorTransformOperation
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Xác định phép biến đổi màu.
type: docs
url: /vi/com.aspose.slides/colortransformoperation/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Xác định phép biến đổi màu.
## Trường

| Trường | Mô tả |
| --- | --- |
| [Tint](#Tint) | Tô màu nhẹ. |
| [Shade](#Shade) | Tối màu. |
| [Complement](#Complement) | Thay đổi màu thành một màu bổ sung RGB. |
| [Inverse](#Inverse) | Thay đổi màu thành màu đảo ngược. |
| [Grayscale](#Grayscale) | Thay đổi màu thành màu xám với độ sáng cùng mức. |
| [SetAlpha](#SetAlpha) | Xác định thành phần alpha của màu. |
| [AddAlpha](#AddAlpha) | Thêm giá trị tham số vào thành phần alpha của màu. |
| [MultiplyAlpha](#MultiplyAlpha) | Nhân thành phần alpha với giá trị tham số. |
| [SetHue](#SetHue) | Thay đổi thành phần hue của màu thành giá trị tham số. |
| [AddHue](#AddHue) | Thêm giá trị tham số vào thành phần hue của màu. |
| [MultiplyHue](#MultiplyHue) | Nhân thành phần hue với giá trị tham số. |
| [SetSaturation](#SetSaturation) | Thay đổi thành phần saturation của màu thành giá trị tham số. |
| [AddSaturation](#AddSaturation) | Thêm giá trị tham số vào thành phần saturation của màu. |
| [MultiplySaturation](#MultiplySaturation) | Nhân thành phần saturation với giá trị tham số. |
| [SetLuminance](#SetLuminance) | Thay đổi thành phần luminance của màu thành giá trị tham số. |
| [AddLuminance](#AddLuminance) | Thêm giá trị tham số vào thành phần luminance của màu. |
| [MultiplyLuminance](#MultiplyLuminance) | Nhân thành phần luminance với giá trị tham số. |
| [SetRed](#SetRed) | Thay đổi thành phần đỏ của màu thành giá trị tham số. |
| [AddRed](#AddRed) | Thêm giá trị tham số vào thành phần đỏ của màu. |
| [MultiplyRed](#MultiplyRed) | Nhân thành phần đỏ với một tham số. |
| [SetGreen](#SetGreen) | Thay đổi thành phần xanh lá của màu thành giá trị tham số. |
| [AddGreen](#AddGreen) | Thêm một tham số vào thành phần xanh lá của màu. |
| [MultiplyGreen](#MultiplyGreen) | Nhân thành phần xanh lá của màu với giá trị tham số. |
| [SetBlue](#SetBlue) | Thay đổi thành phần xanh dương của màu thành giá trị tham số. |
| [AddBlue](#AddBlue) | Thêm giá trị tham số vào thành phần xanh dương của màu. |
| [MultiplyBlue](#MultiplyBlue) | Nhân thành phần xanh dương của màu với giá trị tham số. |
| [Gamma](#Gamma) | Chỉnh sửa gamma. |
| [InverseGamma](#InverseGamma) | Chỉnh sửa gamma ngược. |
### Tô màu {#Tint}
```
public static final int Tint
```

Tô màu nhẹ. Tham số nằm trong khoảng từ 0 (màu gốc) đến 1 (trắng).

### Tối màu {#Shade}
```
public static final int Shade
```

Làm tối màu. Tham số nằm trong khoảng từ 0 (màu gốc) đến 1 (đen).

### Bổ sung {#Complement}
```
public static final int Complement
```

Thay đổi màu thành một màu bổ sung RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Đảo ngược {#Inverse}
```
public static final int Inverse
```

Thay đổi màu thành màu đảo ngược. r = 1 - r; g = 1 - g; b = 1 - b;

### Thang xám {#Grayscale}
```
public static final int Grayscale
```

Thay đổi màu thành một màu xám với độ sáng tương tự. Tham số bị bỏ qua.

### ĐặtAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Xác định thành phần alpha của màu. Tham số nằm trong khoảng từ 0 (trong suốt) đến 1 (độ mờ).

### ThêmAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Thêm giá trị tham số vào thành phần alpha của màu. Tham số nằm trong khoảng từ -1 đến 1.

### NhânAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Nhân thành phần alpha với giá trị tham số.

### ĐặtHue {#SetHue}
```
public static final int SetHue
```

Thay đổi thành phần hue của màu thành giá trị tham số. Tham số nằm trong khoảng từ 0 đến 360.

### ThêmHue {#AddHue}
```
public static final int AddHue
```

Thêm giá trị tham số vào thành phần hue của màu. Tham số nằm trong khoảng từ -360 đến 360.

### NhânHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Nhân thành phần hue với giá trị tham số.

### ĐặtSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Thay đổi thành phần saturation của màu thành giá trị tham số. Tham số nằm trong khoảng từ 0 đến 1.

### ThêmSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Thêm giá trị tham số vào thành phần saturation của màu. Tham số nằm trong khoảng từ -1 đến 1.

### NhânSaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Nhân thành phần saturation với giá trị tham số.

### ĐặtLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Thay đổi thành phần luminance của màu thành giá trị tham số. Tham số nằm trong khoảng từ 0 đến 1.

### ThêmLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Thêm giá trị tham số vào thành phần luminance của màu. Tham số nằm trong khoảng từ -1 đến 1.

### NhânLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Nhân thành phần luminance với giá trị tham số.

### ĐặtRed {#SetRed}
```
public static final int SetRed
```

Thay đổi thành phần đỏ của màu thành giá trị tham số. Tham số nằm trong khoảng từ 0 đến 1.

### ThêmRed {#AddRed}
```
public static final int AddRed
```

Thêm giá trị tham số vào thành phần đỏ của màu. Tham số nằm trong khoảng từ -1 đến 1.

### NhânRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Nhân thành phần đỏ với một tham số.

### ĐặtGreen {#SetGreen}
```
public static final int SetGreen
```

Thay đổi thành phần xanh lá của màu thành giá trị tham số. Tham số nằm trong khoảng từ 0 đến 1.

### ThêmGreen {#AddGreen}
```
public static final int AddGreen
```

Thêm một tham số vào thành phần xanh lá của màu. Tham số nằm trong khoảng từ -1 đến 1.

### NhânGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Nhân thành phần xanh lá của màu với giá trị tham số.

### ĐặtBlue {#SetBlue}
```
public static final int SetBlue
```

Thay đổi thành phần xanh dương của màu thành giá trị tham số. Tham số nằm trong khoảng từ 0 đến 360.

### ThêmBlue {#AddBlue}
```
public static final int AddBlue
```

Thêm giá trị tham số vào thành phần xanh dương của màu. Tham số nằm trong khoảng từ -1 đến 1.

### NhânBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Nhân thành phần xanh dương của màu với giá trị tham số.

### Gamma {#Gamma}
```
public static final int Gamma
```

Chỉnh sửa gamma. Tham số bị bỏ qua.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Chỉnh sửa gamma ngược. Tham số bị bỏ qua.