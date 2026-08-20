---
title: FontSubstitutionInfo
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cấu trúc này đại diện cho thông tin về việc thay thế phông chữ khi nó được hiển thị.
type: docs
url: /vi/com.aspose.slides/fontsubstitutioninfo/
---
**Kế thừa:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Cấu trúc này đại diện cho thông tin về việc thay thế phông chữ khi nó được hiển thị.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Tạo một thể hiện của lớp [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Cho biết tên phông chữ nguồn trong bản trình chiếu. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Cho biết tên phông chữ thay thế cho phông chữ gốc. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Tạo một thể hiện của lớp [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| originFontName | java.lang.String | Tên phông chữ nguồn trong bản trình chiếu String |
| substFontName | java.lang.String | Tên phông chữ thay thế cho phông chữ gốc String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Cho biết tên phông chữ nguồn trong bản trình chiếu. Chỉ đọc String

**Trả về:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Cho biết tên phông chữ thay thế cho phông chữ gốc. Chỉ đọc String

**Trả về:**
java.lang.String