---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một bộ sưu tập các quy tắc FontFallBack được người dùng định nghĩa
type: docs
url: /vi/com.aspose.slides/ifontfallbackrulescollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

Biểu diễn một bộ sưu tập các quy tắc FontFallBack, do người dùng định nghĩa
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy quy tắc tại chỉ mục được chỉ định. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Thêm một quy tắc FallBack mới vào cuối bộ sưu tập. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Xóa lần xuất hiện đầu tiên của một quy tắc FallBack cụ thể khỏi bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


Lấy quy tắc tại chỉ mục được chỉ định. Chỉ đọc [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Lấy bộ sưu tập quy tắc trống hoặc đã được khởi tạo trước từ FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Thêm một số quy tắc vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Lấy đối tượng của quy tắc đầu tiên trong bộ sưu tập
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


Thêm một quy tắc FallBack mới vào cuối bộ sưu tập.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Lấy bộ sưu tập quy tắc trống hoặc đã được khởi tạo trước từ FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Thêm quy tắc mới vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Quy tắc được chỉ định để thêm |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


Xóa lần xuất hiện đầu tiên của một quy tắc FallBack cụ thể khỏi bộ sưu tập.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Lấy bộ sưu tập quy tắc trống hoặc đã được khởi tạo trước từ FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Thêm một số quy tắc vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Lấy đối tượng của quy tắc đầu tiên trong bộ sưu tập
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Xóa 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Quy tắc cần xóa khỏi bộ sưu tập. |