---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Cung cấp các tùy chọn kiểm soát giao diện bố trí ghi chú và bình luận trong tài liệu được xuất.
type: docs
url: /vi/com.aspose.slides/notescommentslayoutingoptions/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Cung cấp các tùy chọn kiểm soát giao diện bố trí ghi chú và bình luận trong tài liệu được xuất.
## Hàm khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Hàm khởi tạo mặc định. |
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Lấy hoặc đặt khả năng hiển thị của các bình luận không có tác giả. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Lấy hoặc đặt khả năng hiển thị của các bình luận không có tác giả. |
| [getNotesPosition()](#getNotesPosition--) | Lấy hoặc đặt vị trí của ghi chú trên trang. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Lấy hoặc đặt vị trí của ghi chú trên trang. |
| [getCommentsPosition()](#getCommentsPosition--) | Lấy hoặc đặt vị trí của các bình luận trên trang. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Lấy hoặc đặt vị trí của các bình luận trên trang. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Lấy hoặc đặt màu của khu vực bình luận (Chỉ áp dụng nếu bình luận được hiển thị ở bên phải). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Lấy hoặc đặt màu của khu vực bình luận (Chỉ áp dụng nếu bình luận được hiển thị ở bên phải). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Lấy hoặc đặt độ rộng của khu vực xuất bình luận bằng pixel (Chỉ áp dụng nếu bình luận được hiển thị ở bên phải). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Lấy hoặc đặt độ rộng của khu vực xuất bình luận bằng pixel (Chỉ áp dụng nếu bình luận được hiển thị ở bên phải). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Hàm khởi tạo mặc định.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Lấy hoặc đặt khả năng hiển thị của các bình luận không có tác giả. Nếu true thì bình luận sẽ được hiển thị. (Chỉ áp dụng nếu bình luận được hiển thị).

--------------------

Giá trị mặc định là **false**.

**Trả về:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Lấy hoặc đặt khả năng hiển thị của các bình luận không có tác giả. Nếu true thì bình luận sẽ được hiển thị. (Chỉ áp dụng nếu bình luận được hiển thị).

--------------------

Giá trị mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

Lấy hoặc đặt vị trí của ghi chú trên trang.

--------------------

Mặc định là **NotesPositions.None**.

**Trả về:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Lấy hoặc đặt vị trí của ghi chú trên trang.

--------------------

Mặc định là **NotesPositions.None**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Lấy hoặc đặt vị trí của các bình luận trên trang.

--------------------

Mặc định là **CommentsPositions.None**.

**Trả về:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Lấy hoặc đặt vị trí của các bình luận trên trang.

--------------------

Mặc định là **CommentsPositions.None**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

Lấy hoặc đặt màu của khu vực bình luận (Chỉ áp dụng nếu bình luận được hiển thị ở bên phải).

--------------------

Mặc định là **SkyBlue**.

**Trả về:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

Lấy hoặc đặt màu của khu vực bình luận (Chỉ áp dụng nếu bình luận được hiển thị ở bên phải).

--------------------

Mặc định là **SkyBlue**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Lấy hoặc đặt độ rộng của khu vực xuất bình luận bằng pixel (Chỉ áp dụng nếu bình luận được hiển thị ở bên phải).

--------------------

Giá trị tối thiểu và mặc định là **150**.

**Trả về:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Lấy hoặc đặt độ rộng của khu vực xuất bình luận bằng pixel (Chỉ áp dụng nếu bình luận được hiển thị ở bên phải).

--------------------

Giá trị tối thiểu và mặc định là **150**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |