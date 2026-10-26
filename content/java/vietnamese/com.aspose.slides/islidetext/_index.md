---
title: ISlideText
second_title: Aspose.Slides for Java Tham chiếu API
description: Biểu diễn văn bản được trích xuất từ slide
type: docs
url: /vi/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Biểu diễn văn bản được trích xuất từ slide
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getText()](#getText--) | Văn bản trên các shape của slide |
| [getMasterText()](#getMasterText--) | Văn bản trên các shape của trang master cho slide này |
| [getLayoutText()](#getLayoutText--) | Văn bản trên các shape của trang bố cục cho slide này |
| [getNotesText()](#getNotesText--) | Văn bản trên các shape của trang ghi chú cho slide này |
| [getCommentsText()](#getCommentsText--) | Văn bản của các bình luận trên slide |
### getText() {#getText--}
```
public abstract String getText()
```


Văn bản trên các shape của slide

**Trả về:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


Văn bản trên các shape của trang master cho slide này

**Trả về:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


Văn bản trên các shape của trang bố cục cho slide này

**Trả về:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


Văn bản trên các shape của trang ghi chú cho slide này

**Trả về:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


Văn bản của các bình luận trên slide

--------------------

Trường này trống khi văn bản được trích xuất bằng chế độ Arranged.

**Trả về:**
java.lang.String