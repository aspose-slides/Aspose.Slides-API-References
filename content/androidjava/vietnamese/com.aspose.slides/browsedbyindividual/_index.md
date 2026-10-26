---
title: BrowsedByIndividual
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cửa sổ duyệt theo cá nhân
type: docs
url: /vi/com.aspose.slides/browsedbyindividual/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Duyệt theo cá nhân (cửa sổ)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Khởi tạo một thể hiện mới của lớp BrowsedByIndividual. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Hiển thị thanh cuộn trong cửa sổ |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Hiển thị thanh cuộn trong cửa sổ |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Khởi tạo một thể hiện mới của lớp BrowsedByIndividual.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```


Hiển thị thanh cuộn trong cửa sổ

**Trả về:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Hiển thị thanh cuộn trong cửa sổ

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |