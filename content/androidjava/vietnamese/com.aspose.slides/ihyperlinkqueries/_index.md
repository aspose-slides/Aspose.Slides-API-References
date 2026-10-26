---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: Cung cấp quyền truy cập dễ dàng vào các liên kết siêu văn bản được chứa.
type: docs
url: /vi/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Cung cấp quyền truy cập dễ dàng vào các liên kết siêu văn bản được chứa.
## Phương thức

| Method | Description |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Lấy tất cả các đối tượng con IHyperlinkContainer chứa HyperlinkClick không null. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Lấy tất cả các đối tượng con IHyperlinkContainer chứa HyperlinkMouseOver không null. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Lấy tất cả các đối tượng con IHyperlinkContainer chứa HyperlinkMouseOver không null. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Xóa tất cả các liên kết HyperlinkClick và HyperlinkMouseOver được chứa (trong tất cả các đối tượng con IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


Lấy tất cả các đối tượng con IHyperlinkContainer chứa HyperlinkClick không null. Với đối tượng IHyperlinkContainer đã cho, bạn có thể quản lý liên kết siêu văn bản của nó (đọc, cập nhật hoặc xóa). Xem giao diện IHyperlinkContainer.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Tất cả các đối tượng con IHyperlinkContainer chứa HyperlinkClick không null
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


Lấy tất cả các đối tượng con IHyperlinkContainer chứa HyperlinkMouseOver không null. Với đối tượng IHyperlinkContainer đã cho, bạn có thể quản lý liên kết siêu văn bản của nó (đọc, cập nhật hoặc xóa). Xem giao diện IHyperlinkContainer.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Tất cả các đối tượng con IHyperlinkContainer chứa HyperlinkMouseOver không null
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


Lấy tất cả các đối tượng con IHyperlinkContainer chứa HyperlinkMouseOver không null. Với đối tượng IHyperlinkContainer đã cho, bạn có thể quản lý liên kết siêu văn bản của nó (đọc, cập nhật hoặc xóa). Xem giao diện IHyperlinkContainer.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Tất cả các đối tượng con IHyperlinkContainer chứa HyperlinkMouseOver không null
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```


Xóa tất cả các liên kết HyperlinkClick và HyperlinkMouseOver được chứa (trong tất cả các đối tượng con IHyperlinkContainer).