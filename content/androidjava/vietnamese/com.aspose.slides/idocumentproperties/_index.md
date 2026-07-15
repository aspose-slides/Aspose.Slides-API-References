---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents properties of a presentation.
type: docs
url: /vi/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Đại diện cho các thuộc tính của một bài thuyết trình.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Trả về phiên bản ứng dụng. |
| [getNameOfApplication()](#getNameOfApplication--) | Trả về hoặc thiết lập tên của ứng dụng. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Trả về hoặc thiết lập tên của ứng dụng. |
| [getCompany()](#getCompany--) | Trả về hoặc thiết lập thuộc tính công ty. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Trả về hoặc thiết lập thuộc tính công ty. |
| [getManager()](#getManager--) | Trả về hoặc thiết lập thuộc tính quản lý. |
| [setManager(String value)](#setManager-java.lang.String-) | Trả về hoặc thiết lập thuộc tính quản lý. |
| [getPresentationFormat()](#getPresentationFormat--) | Trả về hoặc thiết lập định dạng dự định của một bài thuyết trình. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Trả về hoặc thiết lập định dạng dự định của một bài thuyết trình. |
| [getSharedDoc()](#getSharedDoc--) | Xác định xem bài thuyết trình có được chia sẻ giữa nhiều người không. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Xác định xem bài thuyết trình có được chia sẻ giữa nhiều người không. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Trả về hoặc thiết lập mẫu của một ứng dụng. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Trả về hoặc thiết lập mẫu của một ứng dụng. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Thời gian chỉnh sửa tổng cộng của một bài thuyết trình. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Thời gian chỉnh sửa tổng cộng của một bài thuyết trình. |
| [getTitle()](#getTitle--) | Trả về hoặc thiết lập tiêu đề của một bài thuyết trình. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Trả về hoặc thiết lập tiêu đề của một bài thuyết trình. |
| [getSubject()](#getSubject--) | Trả về hoặc thiết lập chủ đề của một bài thuyết trình. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Trả về hoặc thiết lập chủ đề của một bài thuyết trình. |
| [getAuthor()](#getAuthor--) | Trả về hoặc thiết lập tác giả của một bài thuyết trình. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Trả về hoặc thiết lập tác giả của một bài thuyết trình. |
| [getKeywords()](#getKeywords--) | Trả về hoặc thiết lập các từ khóa của một bài thuyết trình. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Trả về hoặc thiết lập các từ khóa của một bài thuyết trình. |
| [getComments()](#getComments--) | Trả về hoặc thiết lập bình luận của một bài thuyết trình. |
| [setComments(String value)](#setComments-java.lang.String-) | Trả về hoặc thiết lập bình luận của một bài thuyết trình. |
| [getCategory()](#getCategory--) | Trả về hoặc thiết lập danh mục của một bài thuyết trình. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Trả về hoặc thiết lập danh mục của một bài thuyết trình. |
| [getCreatedTime()](#getCreatedTime--) | Trả về ngày tạo của một bài thuyết trình. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Trả về ngày tạo của một bài thuyết trình. |
| [getLastSavedTime()](#getLastSavedTime--) | Trả về ngày mà một bài thuyết trình được chỉnh sửa lần cuối. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Trả về ngày mà một bài thuyết trình được chỉnh sửa lần cuối. |
| [getLastPrinted()](#getLastPrinted--) | Trả về ngày mà một bài thuyết trình được in lần cuối. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Trả về ngày mà một bài thuyết trình được in lần cuối. |
| [getLastSavedBy()](#getLastSavedBy--) | Trả về hoặc thiết lập tên của người cuối cùng đã chỉnh sửa một bài thuyết trình. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Trả về hoặc thiết lập tên của người cuối cùng đã chỉnh sửa một bài thuyết trình. |
| [getRevisionNumber()](#getRevisionNumber--) | Trả về hoặc thiết lập số phiên bản của bài thuyết trình. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Trả về hoặc thiết lập số phiên bản của bài thuyết trình. |
| [getContentStatus()](#getContentStatus--) | Trả về hoặc thiết lập trạng thái nội dung của một bài thuyết trình. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Trả về hoặc thiết lập trạng thái nội dung của một bài thuyết trình. |
| [getContentType()](#getContentType--) | Trả về hoặc thiết lập loại nội dung của một bài thuyết trình. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Trả về hoặc thiết lập loại nội dung của một bài thuyết trình. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Trả về hoặc thiết lập thuộc tính tài liệu HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Trả về hoặc thiết lập thuộc tính tài liệu HyperlinkBase. |
| [getScaleCrop()](#getScaleCrop--) | Cho biết chế độ hiển thị của hình thu nhỏ tài liệu. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Cho biết chế độ hiển thị của hình thu nhỏ tài liệu. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Cho biết liệu các siêu liên kết trong tài liệu có cập nhật hay không. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Cho biết liệu các siêu liên kết trong tài liệu có cập nhật hay không. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được nhà sản xuất cập nhật độc quyền trong phần này. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được nhà sản xuất cập nhật độc quyền trong phần này. |
| [getSlides()](#getSlides--) | Chỉ định tổng số slide trong tài liệu bài thuyết trình. |
| [getHiddenSlides()](#getHiddenSlides--) | Chỉ định số slide ẩn trong tài liệu bài thuyết trình. |
| [getNotes()](#getNotes--) | Chỉ định số slide trong một bài thuyết trình có chứa ghi chú. |
| [getParagraphs()](#getParagraphs--) | Chỉ định tổng số đoạn được tìm thấy trong tài liệu nếu áp dụng. |
| [getWords()](#getWords--) | Chỉ định tổng số từ có trong tài liệu. |
| [getMultimediaClips()](#getMultimediaClips--) | Chỉ định tổng số đoạn âm thanh hoặc video có trong tài liệu. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Chỉ định tiêu đề của mỗi phần tài liệu. |
| [getHeadingPairs()](#getHeadingPairs--) | Cho biết việc nhóm các phần tài liệu và số phần trong mỗi nhóm. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Trả về số lượng thuộc tính tùy chỉnh thực sự chứa trong một bộ sưu tập. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Trả về tên thuộc tính tùy chỉnh tại chỉ mục được chỉ định. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Xóa một thuộc tính tùy chỉnh liên kết với tên đã chỉ định. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Kiểm tra sự tồn tại của một thuộc tính tùy chỉnh với tên đã chỉ định. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Trả về hoặc thiết lập thuộc tính tùy chỉnh liên kết với tên đã chỉ định. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Trả về hoặc thiết lập thuộc tính tùy chỉnh liên kết với tên đã chỉ định. |
| [clearCustomProperties()](#clearCustomProperties--) | Xóa tất cả các thuộc tính tùy chỉnh. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Xóa và đặt giá trị mặc định cho tất cả các thuộc tính builtIn. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Sets a named boolean custom property. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Sets a named integer custom property. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Sets a named DateTime custom property. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Sets a named string custom property. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Sets a named float custom property. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Sets a named double custom property. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Trả về phiên bản ứng dụng. Chỉ đọc String.

--------------------

Nội dung của phần tử này phải ở dạng XX.YYYY, trong đó X và Y là các giá trị số; nếu không, tài liệu sẽ được coi là không tuân thủ. Aspose.Slides biểu thị phiên bản của nó theo định dạng XX.YY.ZZ, trong đó: XX - phiên bản chính YY - phiên bản phụ ZZ - phiên bản vá. Ví dụ, giá trị 23.0105 có nghĩa là phiên bản Aspose.Slides 23.1.5.

**Trả về:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Trả về hoặc thiết lập tên của ứng dụng. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Trả về hoặc thiết lập tên của ứng dụng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Trả về hoặc thiết lập thuộc tính công ty. Đọc/ghi String.

**Trả về:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Trả về hoặc thiết lập thuộc tính công ty. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Trả về hoặc thiết lập thuộc tính quản lý. Đọc/ghi String.

**Trả về:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Trả về hoặc thiết lập thuộc tính quản lý. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Trả về hoặc thiết lập định dạng dự định của một bài thuyết trình. Đọc/ghi String.

**Trả về:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Trả về hoặc thiết lập định dạng dự định của một bài thuyết trình. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Xác định xem bài thuyết trình có được chia sẻ giữa nhiều người không. Đọc/ghi boolean.

**Trả về:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Xác định xem bài thuyết trình có được chia sẻ giữa nhiều người không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Trả về hoặc thiết lập mẫu của một ứng dụng. Đọc/ghi String.

**Trả về:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Trả về hoặc thiết lập mẫu của một ứng dụng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Thời gian chỉnh sửa tổng cộng của một bài thuyết trình. Đọc/ghi double.

**Trả về:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Thời gian chỉnh sửa tổng cộng của một bài thuyết trình. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Trả về hoặc thiết lập tiêu đề của một bài thuyết trình. Đọc/ghi String.

**Trả về:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Trả về hoặc thiết lập tiêu đề của một bài thuyết trình. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Trả về hoặc thiết lập chủ đề của một bài thuyết trình. Đọc/ghi String.

**Trả về:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Trả về hoặc thiết lập chủ đề của một bài thuyết trình. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Trả về hoặc thiết lập tác giả của một bài thuyết trình. Đọc/ghi String.

**Trả về:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Trả về hoặc thiết lập tác giả của một bài thuyết trình. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Trả về hoặc thiết lập các từ khóa của một bài thuyết trình. Đọc/ghi String.

**Trả về:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Trả về hoặc thiết lập các từ khóa của một bài thuyết trình. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Trả về hoặc thiết lập bình luận của một bài thuyết trình. Đọc/ghi String.

**Trả về:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Trả về hoặc thiết lập bình luận của một bài thuyết trình. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Trả về hoặc thiết lập danh mục của một bài thuyết trình. Đọc/ghi String.

**Trả về:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Trả về hoặc thiết lập danh mục của một bài thuyết trình. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Trả về ngày tạo của một bài thuyết trình. Giá trị theo UTC. Đọc/ghi java.util.Date.

**Trả về:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Trả về ngày tạo của một bài thuyết trình. Giá trị theo UTC. Đọc/ghi java.util.Date.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Trả về ngày mà một bài thuyết trình được chỉnh sửa lần cuối. Giá trị theo UTC. Chỉ đọc trong trường hợp Presentation.DocumentProperties (vì sẽ được cập nhật nội bộ trong quá trình lưu đối tượng IPresentation). Có thể thay đổi qua thể hiện DocumentProperties trả về bởi phương thức [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Vui lòng xem ví dụ trong phần tóm tắt phương thức [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Trả về:**
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Trả về ngày mà một bài thuyết trình được chỉnh sửa lần cuối. Giá trị theo UTC. Chỉ đọc trong trường hợp Presentation.DocumentProperties (vì sẽ được cập nhật nội bộ trong quá trình lưu đối tượng IPresentation). Có thể thay đổi qua thể hiện DocumentProperties trả về bởi phương thức [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Vui lòng xem ví dụ trong phần tóm tắt phương thức [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Trả về ngày mà một bài thuyết trình được in lần cuối. Đọc/ghi java.util.Date.

**Trả về:**
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Trả về ngày mà một bài thuyết trình được in lần cuối. Đọc/ghi java.util.Date.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Trả về hoặc thiết lập tên của người cuối cùng đã chỉnh sửa một bài thuyết trình. Đọc/ghi String.

**Trả về:**
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Trả về hoặc thiết lập tên của người cuối cùng đã chỉnh sửa một bài thuyết trình. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Trả về hoặc thiết lập số phiên bản của bài thuyết trình. Đọc/ghi int.

**Trả về:**
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Trả về hoặc thiết lập số phiên bản của bài thuyết trình. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Trả về hoặc thiết lập trạng thái nội dung của một bài thuyết trình. Đọc/ghi String.

**Trả về:**
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Trả về hoặc thiết lập trạng thái nội dung của một bài thuyết trình. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Trả về hoặc thiết lập loại nội dung của một bài thuyết trình. Đọc/ghi String.

**Trả về:**
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Trả về hoặc thiết lập loại nội dung của một bài thuyết trình. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Trả về hoặc thiết lập thuộc tính tài liệu HyperlinkBase. Đọc/ghi String.

**Trả về:**
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Trả về hoặc thiết lập thuộc tính tài liệu HyperlinkBase. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Cho biết chế độ hiển thị của hình thu nhỏ tài liệu. Đặt phần tử này là **true** để cho phép phóng to hình thu nhỏ tài liệu tới màn hình. Đặt phần tử này là **false** để cho phép cắt hình thu nhỏ tài liệu chỉ hiển thị các phần phù hợp với màn hình. Đọc/ghi boolean.

**Trả về:**
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Cho biết chế độ hiển thị của hình thu nhỏ tài liệu. Đặt phần tử này là **true** để cho phép phóng to hình thu nhỏ tài liệu tới màn hình. Đặt phần tử này là **false** để cho phép cắt hình thu nhỏ tài liệu chỉ hiển thị các phần phù hợp với màn hình. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Cho biết liệu các siêu liên kết trong tài liệu có cập nhật hay không. Đặt phần tử này là **true** để chỉ ra rằng các siêu liên kết đã được cập nhật. Đặt phần tử này là **false** để chỉ ra rằng các siêu liên kết đã lỗi thời. Đọc/ghi boolean.

**Trả về:**
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Cho biết liệu các siêu liên kết trong tài liệu có cập nhật hay không. Đặt phần tử này là **true** để chỉ ra rằng các siêu liên kết đã được cập nhật. Đặt phần tử này là **false** để chỉ ra rằng các siêu liên kết đã lỗi thời. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được nhà sản xuất cập nhật độc quyền trong phần này. Nhà sản xuất tiếp theo mở tài liệu này sẽ cập nhật các mối quan hệ siêu liên kết với các siêu liên kết mới được chỉ định trong phần này. Đọc/ghi boolean.

**Trả về:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được nhà sản xuất cập nhật độc quyền trong phần này. Nhà sản xuất tiếp theo mở tài liệu này sẽ cập nhật các mối quan hệ siêu liên kết với các siêu liên kết mới được chỉ định trong phần này. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Chỉ định tổng số slide trong tài liệu bài thuyết trình. Chỉ đọc int.

**Trả về:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Chỉ định số slide ẩn trong tài liệu bài thuyết trình. Chỉ đọc int.

**Trả về:**
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Chỉ định số slide trong một bài thuyết trình có chứa ghi chú. Chỉ đọc int.

**Trả về:**
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Chỉ định tổng số đoạn được tìm thấy trong tài liệu nếu áp dụng. Chỉ đọc int.

**Trả về:**
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

Chỉ định tổng số từ có trong tài liệu. Chỉ đọc int.

**Trả về:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Chỉ định tổng số đoạn âm thanh hoặc video có trong tài liệu. Chỉ đọc int.

**Trả về:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Chỉ định tiêu đề của mỗi phần tài liệu. Các phần này không phải là phần tài liệu thực tế mà là các biểu diễn khái niệm của các phần tài liệu. Chỉ đọc String[].

**Trả về:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Cho biết việc nhóm các phần tài liệu và số phần trong mỗi nhóm. Chỉ đọc IHeadingPair[].

**Trả về:**
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Trả về số lượng thuộc tính tùy chỉnh thực sự chứa trong một bộ sưu tập. Chỉ đọc int.

**Trả về:**
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Trả về tên thuộc tính tùy chỉnh tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của thuộc tính tùy chỉnh cần lấy. |

**Trả về:**
java.lang.String - Tên thuộc tính tùy chỉnh tại chỉ mục được chỉ định.

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Xóa một thuộc tính tùy chỉnh liên kết với tên đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần xóa. |

**Trả về:**
boolean - Trả về true nếu thuộc tính đã bị xóa, false nếu không.

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Kiểm tra sự tồn tại của một thuộc tính tùy chỉnh với tên đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần kiểm tra. |

**Trả về:**
boolean - Trả về true nếu thuộc tính tồn tại, false nếu không.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Trả về hoặc thiết lập thuộc tính tùy chỉnh liên kết với tên đã chỉ định. Đọc/ghi Object.

--------------------

Giá trị có thể là **int**, **float**, **double**, **String**, **boolean** hoặc **Date**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String |  |

**Trả về:**
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Trả về hoặc thiết lập thuộc tính tùy chỉnh liên kết với tên đã chỉ định. Đọc/ghi Object.

--------------------

Giá trị có thể là **int**, **float**, **double**, **String**, **boolean** hoặc **Date**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Xóa tất cả các thuộc tính tùy chỉnh.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Xóa và đặt giá trị mặc định cho tất cả các thuộc tính builtIn.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Lấy giá trị boolean có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy |
| value | boolean[] | Giá trị thuộc tính tùy chỉnh |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Lấy giá trị integer có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy |
| value | int[] | Giá trị thuộc tính tùy chỉnh |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Lấy giá trị DateTime có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy |
| value | java.util.Date[] | Giá trị thuộc tính tùy chỉnh |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Lấy giá trị string có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy |
| value | java.lang.String[] | Giá trị thuộc tính tùy chỉnh |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Lấy giá trị float có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy |
| value | float[] | Giá trị thuộc tính tùy chỉnh |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Lấy giá trị double có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy. |
| value | double[] | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Đặt một thuộc tính tùy chỉnh boolean có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần đặt |
| value | boolean | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Đặt một thuộc tính tùy chỉnh integer có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần đặt |
| value | int | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Đặt một thuộc tính tùy chỉnh DateTime có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần đặt |
| value | java.util.Date | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Đặt một thuộc tính tùy chỉnh string có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần đặt |
| value | java.lang.String | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Đặt một thuộc tính tùy chỉnh float có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần đặt |
| value | float | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Đặt một thuộc tính tùy chỉnh double có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần đặt |
| value | double | Giá trị thuộc tính tùy chỉnh |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Lấy một mảng các nhãn độ nhạy từ các thuộc tính tài liệu tùy chỉnh (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
com.aspose.slides.ISensitivityLabel[]