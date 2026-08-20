---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Cung cấp cách truy cập dễ dàng tới các siêu liên kết được chứa.
type: docs
url: /vi/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Cung cấp cách truy cập dễ dàng tới các siêu liên kết được chứa.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Lấy tất cả các đối tượng con IHyperlinkContainer có HyperlinkClick không null. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Lấy tất cả các đối tượng con IHyperlinkContainer có HyperlinkMouseOver không null. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Lấy tất cả các đối tượng con IHyperlinkContainer có HyperlinkMouseOver không null. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Xóa tất cả các siêu liên kết HyperlinkClick và HyperlinkMouseOver được chứa (trong tất cả các đối tượng con IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


Lấy tất cả các đối tượng con IHyperlinkContainer có HyperlinkClick không null. Với đối tượng IHyperlinkContainer được cung cấp, bạn có thể quản lý siêu liên kết của nó (đọc, cập nhật hoặc xóa). Xem giao diện IHyperlinkContainer.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Tất cả các đối tượng con IHyperlinkContainer có HyperlinkClick không null
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


Lấy tất cả các đối tượng con IHyperlinkContainer có HyperlinkMouseOver không null. Với đối tượng IHyperlinkContainer được cung cấp, bạn có thể quản lý siêu liên kết của nó (đọc, cập nhật hoặc xóa). Xem giao diện IHyperlinkContainer.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Tất cả các đối tượng con IHyperlinkContainer có HyperlinkMouseOver không null
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


Lấy tất cả các đối tượng con IHyperlinkContainer có HyperlinkMouseOver không null. Với đối tượng IHyperlinkContainer được cung cấp, bạn có thể quản lý siêu liên kết của nó (đọc, cập nhật hoặc xóa). Xem giao diện IHyperlinkContainer.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Tất cả các đối tượng con IHyperlinkContainer có HyperlinkMouseOver không null
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```


Xóa tất cả các siêu liên kết HyperlinkClick và HyperlinkMouseOver được chứa (trong tất cả các đối tượng con IHyperlinkContainer).