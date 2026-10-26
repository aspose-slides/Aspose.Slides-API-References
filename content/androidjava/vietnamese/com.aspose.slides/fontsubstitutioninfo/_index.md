---
title: FontSubstitutionInfo
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Cấu trúc này biểu thị thông tin về việc thay thế phông chữ khi nó sẽ được hiển thị.
type: docs
url: /vi/com.aspose.slides/fontsubstitutioninfo/
---
**Kế thừa:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Cấu trúc này biểu thị thông tin về việc thay thế phông chữ khi nó sẽ được hiển thị.

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
## Phương thức khởi tạo

| Constructor | Description |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Tạo một thể hiện của lớp [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Phương thức

| Method | Description |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Cho biết tên phông nguồn trong bản trình chiếu. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Cho biết tên phông thay thế cho phông gốc. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

Tạo một thể hiện của lớp [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| originFontName | java.lang.String | Tên phông nguồn trong bản trình chiếu String |
| substFontName | java.lang.String | Tên phông thay thế cho phông gốc String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

Cho biết tên phông nguồn trong bản trình chiếu. Chỉ đọc String

**Trả về:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

Cho biết tên phông thay thế cho phông gốc. Chỉ đọc String

**Trả về:**
java.lang.String