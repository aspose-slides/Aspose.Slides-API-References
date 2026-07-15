---
title: DocumentProperties
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho các thuộc tính của một bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/documentproperties/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Đại diện cho các thuộc tính của một bản trình chiếu.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Khởi tạo lớp Presentation đại diện cho bản trình chiếu
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Tạo một tham chiếu đến đối tượng IDocumentProperties liên kết với Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Hiển thị các thuộc tính tích hợp sẵn
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Khởi tạo lớp Presentation đại diện cho Presentation
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Tạo một tham chiếu đến đối tượng IDocumentProperties liên kết với Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Đặt các thuộc tính tích hợp sẵn
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Lưu bản trình chiếu của bạn vào tệp
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Khởi tạo một thể hiện mới của lớp [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Trả về phiên bản ứng dụng. |
| [getNameOfApplication()](#getNameOfApplication--) | Trả về hoặc thiết lập tên của ứng dụng. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Trả về hoặc thiết lập tên của ứng dụng. |
| [getCompany()](#getCompany--) | Trả về hoặc thiết lập tên của ứng dụng. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Trả về hoặc thiết lập tên của ứng dụng. |
| [getManager()](#getManager--) | Trả về hoặc thiết lập tên của người quản lý. |
| [setManager(String value)](#setManager-java.lang.String-) | Trả về hoặc thiết lập tên của người quản lý. |
| [getPresentationFormat()](#getPresentationFormat--) | Trả về hoặc thiết lập định dạng dự định của một bản trình chiếu. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Trả về hoặc thiết lập định dạng dự định của một bản trình chiếu. |
| [getSharedDoc()](#getSharedDoc--) | Xác định xem bản trình chiếu có được chia sẻ giữa nhiều người hay không. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Xác định xem bản trình chiếu có được chia sẻ giữa nhiều người hay không. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Trả về hoặc thiết lập mẫu của một ứng dụng. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Trả về hoặc thiết lập mẫu của một ứng dụng. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Thời gian chỉnh sửa tổng cộng của một bản trình chiếu. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Thời gian chỉnh sửa tổng cộng của một bản trình chiếu. |
| [getTitle()](#getTitle--) | Trả về hoặc thiết lập tiêu đề của một bản trình chiếu. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Trả về hoặc thiết lập tiêu đề của một bản trình chiếu. |
| [getSubject()](#getSubject--) | Trả về hoặc thiết lập chủ đề của một bản trình chiếu. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Trả về hoặc thiết lập chủ đề của một bản trình chiếu. |
| [getAuthor()](#getAuthor--) | Trả về hoặc thiết lập tác giả của một bản trình chiếu. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Trả về hoặc thiết lập tác giả của một bản trình chiếu. |
| [getKeywords()](#getKeywords--) | Trả về hoặc thiết lập các từ khóa của một bản trình chiếu. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Trả về hoặc thiết lập các từ khóa của một bản trình chiếu. |
| [getComments()](#getComments--) | Trả về hoặc thiết lập nhận xét của một bản trình chiếu. |
| [setComments(String value)](#setComments-java.lang.String-) | Trả về hoặc thiết lập nhận xét của một bản trình chiếu. |
| [getCategory()](#getCategory--) | Trả về hoặc thiết lập danh mục của một bản trình chiếu. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Trả về hoặc thiết lập danh mục của một bản trình chiếu. |
| [getCreatedTime()](#getCreatedTime--) | Trả về ngày một bản trình chiếu được tạo. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Trả về ngày một bản trình chiếu được tạo. |
| [getLastSavedTime()](#getLastSavedTime--) | Trả về ngày một bản trình chiếu được sửa đổi lần cuối. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Trả về ngày một bản trình chiếu được sửa đổi lần cuối. |
| [getLastPrinted()](#getLastPrinted--) | Trả về ngày khi một bản trình chiếu được in lần cuối. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Trả về ngày khi một bản trình chiếu được in lần cuối. |
| [getLastSavedBy()](#getLastSavedBy--) | Trả về hoặc thiết lập tên của người sửa đổi cuối cùng một bản trình chiếu. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Trả về hoặc thiết lập tên của người sửa đổi cuối cùng một bản trình chiếu. |
| [getRevisionNumber()](#getRevisionNumber--) | Trả về hoặc thiết lập số phiên bản của bản trình chiếu. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Trả về hoặc thiết lập số phiên bản của bản trình chiếu. |
| [getContentStatus()](#getContentStatus--) | Trả về hoặc thiết lập trạng thái nội dung của một bản trình chiếu. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Trả về hoặc thiết lập trạng thái nội dung của một bản trình chiếu. |
| [getContentType()](#getContentType--) | Trả về hoặc thiết lập loại nội dung của một bản trình chiếu. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Trả về hoặc thiết lập loại nội dung của một bản trình chiếu. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Trả về hoặc thiết lập thuộc tính tài liệu HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Trả về hoặc thiết lập thuộc tính tài liệu HyperlinkBase. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Trả về số lượng thuộc tính tùy chỉnh thực sự có trong một bộ sưu tập. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Trả về tên thuộc tính tùy chỉnh tại chỉ mục được chỉ định. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Xóa một thuộc tính tùy chỉnh liên kết với tên được chỉ định. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Kiểm tra sự tồn tại của một thuộc tính tùy chỉnh với tên được chỉ định. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Trả về hoặc thiết lập thuộc tính tùy chỉnh liên kết với tên được chỉ định. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Trả về hoặc thiết lập thuộc tính tùy chỉnh liên kết với tên được chỉ định. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Thiết lập một thuộc tính tùy chỉnh kiểu boolean có tên. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Thiết lập một thuộc tính tùy chỉnh kiểu integer có tên. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Thiết lập một thuộc tính tùy chỉnh kiểu DateTime có tên. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Thiết lập một thuộc tính tùy chỉnh kiểu string có tên. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Thiết lập một thuộc tính tùy chỉnh kiểu float có tên. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Thiết lập một thuộc tính tùy chỉnh kiểu double có tên. |
| [clearCustomProperties()](#clearCustomProperties--) | Xóa tất cả các thuộc tính tùy chỉnh. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Lấy một mảng các nhãn nhạy cảm từ các thuộc tính tài liệu tùy chỉnh (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Xóa và đặt lại giá trị mặc định cho tất cả các thuộc tính builtIn. |
| [getScaleCrop()](#getScaleCrop--) | Chỉ ra chế độ hiển thị của ảnh thu nhỏ tài liệu. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Chỉ ra chế độ hiển thị của ảnh thu nhỏ tài liệu. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Chỉ ra liệu các siêu liên kết trong tài liệu có cập nhật hay không. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Chỉ ra liệu các siêu liên kết trong tài liệu có cập nhật hay không. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được cập nhật độc quyền trong phần này bởi một nhà sản xuất. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được cập nhật độc quyền trong phần này bởi một nhà sản xuất. |
| [getSlides()](#getSlides--) | Trả về tổng số slide trong tài liệu bản trình chiếu. |
| [getHiddenSlides()](#getHiddenSlides--) | Trả về số slide ẩn trong tài liệu bản trình chiếu. |
| [getNotes()](#getNotes--) | Trả về số slide trong bản trình chiếu có ghi chú. |
| [getParagraphs()](#getParagraphs--) | Trả về tổng số đoạn được tìm thấy trong tài liệu nếu áp dụng. |
| [getWords()](#getWords--) | Trả về tổng số từ trong tài liệu. |
| [getMultimediaClips()](#getMultimediaClips--) | Trả về tổng số đoạn âm thanh hoặc video có trong tài liệu. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Chỉ định tiêu đề của mỗi phần tài liệu. |
| [getHeadingPairs()](#getHeadingPairs--) | Chỉ ra cách nhóm các phần tài liệu và số lượng phần trong mỗi nhóm. |
| [deepClone()](#deepClone--) | Sao chép đối tượng hiện tại |
| [cloneT()](#cloneT--) | Sao chép đối tượng hiện tại |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Khởi tạo một thể hiện mới của lớp [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Trả về phiên bản ứng dụng. Chỉ đọc String.

**Trả về:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Trả về hoặc thiết lập tên của ứng dụng. Đọc/ghi String.

**Trả về:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Trả về hoặc thiết lập tên của ứng dụng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

Trả về hoặc thiết lập thuộc tính công ty. Đọc/ghi String.

**Trả về:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Trả về hoặc thiết lập thuộc tính công ty. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

Trả về hoặc thiết lập thuộc tính người quản lý. Đọc/ghi String.

**Trả về:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Trả về hoặc thiết lập thuộc tính người quản lý. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Trả về hoặc thiết lập định dạng dự định của một bản trình chiếu. Đọc/ghi String.

**Trả về:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Trả về hoặc thiết lập định dạng dự định của một bản trình chiếu. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Xác định xem bản trình chiếu có được chia sẻ giữa nhiều người hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Xác định xem bản trình chiếu có được chia sẻ giữa nhiều người hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Trả về hoặc thiết lập mẫu của một ứng dụng. Đọc/ghi String.

**Trả về:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Trả về hoặc thiết lập mẫu của một ứng dụng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Thời gian chỉnh sửa tổng cộng của một bản trình chiếu. Đọc/ghi double.

**Trả về:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Thời gian chỉnh sửa tổng cộng của một bản trình chiếu. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Trả về hoặc thiết lập tiêu đề của một bản trình chiếu. Đọc/ghi String.

**Trả về:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Trả về hoặc thiết lập tiêu đề của một bản trình chiếu. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

Trả về hoặc thiết lập chủ đề của một bản trình chiếu. Đọc/ghi String.

**Trả về:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Trả về hoặc thiết lập chủ đề của một bản trình chiếu. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Trả về hoặc thiết lập tác giả của một bản trình chiếu. Đọc/ghi String.

**Trả về:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Trả về hoặc thiết lập tác giả của một bản trình chiếu. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Trả về hoặc thiết lập các từ khóa của một bản trình chiếu. Đọc/ghi String.

**Trả về:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Trả về hoặc thiết lập các từ khóa của một bản trình chiếu. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

Trả về hoặc thiết lập nhận xét của một bản trình chiếu. Đọc/ghi String.

**Trả về:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Trả về hoặc thiết lập nhận xét của một bản trình chiếu. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

Trả về hoặc thiết lập danh mục của một bản trình chiếu. Đọc/ghi String.

**Trả về:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Trả về hoặc thiết lập danh mục của một bản trình chiếu. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Trả về ngày một bản trình chiếu được tạo. Giá trị ở múi giờ UTC. Đọc/ghi java.util.Date.

**Trả về:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Trả về ngày một bản trình chiếu được tạo. Giá trị ở múi giờ UTC. Đọc/ghi java.util.Date.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Trả về ngày một bản trình chiếu được sửa đổi lần cuối. Giá trị ở múi giờ UTC. Chỉ đọc trong trường hợp Presentation.DocumentProperties (vì sẽ được cập nhật nội bộ trong quá trình lưu đối tượng IPresentation). Có thể thay đổi thông qua thể hiện DocumentProperties trả về bởi phương thức [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Vui lòng xem ví dụ trong tóm tắt phương thức [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Trả về:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Trả về ngày một bản trình chiếu được sửa đổi lần cuối. Giá trị ở múi giờ UTC. Chỉ đọc trong trường hợp Presentation.DocumentProperties (vì sẽ được cập nhật nội bộ trong quá trình lưu đối tượng IPresentation). Có thể thay đổi thông qua thể hiện DocumentProperties trả về bởi phương thức [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Vui lòng xem ví dụ trong tóm tắt phương thức [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Trả về ngày khi một bản trình chiếu được in lần cuối. Đọc/ghi java.util.Date.

**Trả về:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Trả về ngày khi một bản trình chiếu được in lần cuối. Đọc/ghi java.util.Date.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Trả về hoặc thiết lập tên của người sửa đổi cuối cùng một bản trình chiếu. Đọc/ghi String.

**Trả về:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Trả về hoặc thiết lập tên của người sửa đổi cuối cùng một bản trình chiếu. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Trả về hoặc thiết lập số phiên bản của bản trình chiếu. Đọc/ghi int.

**Trả về:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Trả về hoặc thiết lập số phiên bản của bản trình chiếu. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Trả về hoặc thiết lập trạng thái nội dung của một bản trình chiếu. Đọc/ghi String.

**Trả về:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Trả về hoặc thiết lập trạng thái nội dung của một bản trình chiếu. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Trả về hoặc thiết lập loại nội dung của một bản trình chiếu. Đọc/ghi String.

**Trả về:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Trả về hoặc thiết lập loại nội dung của một bản trình chiếu. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Trả về hoặc thiết lập thuộc tính tài liệu HyperlinkBase. Đọc/ghi String.

**Trả về:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Trả về hoặc thiết lập thuộc tính tài liệu HyperlinkBase. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Trả về số lượng thuộc tính tùy chỉnh thực sự có trong một bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Trả về tên thuộc tính tùy chỉnh tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên zero của thuộc tính tùy chỉnh cần lấy. |

**Trả về:**
java.lang.String - Tên thuộc tính tùy chỉnh tại chỉ mục được chỉ định.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Xóa một thuộc tính tùy chỉnh liên kết với tên được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần xóa. |

**Trả về:**
boolean - Trả về true nếu thuộc tính đã bị xóa, false nếu không.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Kiểm tra sự tồn tại của một thuộc tính tùy chỉnh với tên được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần kiểm tra. |

**Trả về:**
boolean - Trả về true nếu thuộc tính tồn tại, false nếu không.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Trả về hoặc thiết lập thuộc tính tùy chỉnh liên kết với tên được chỉ định. Đọc/ghi Object.

--------------------

Giá trị có thể là **int**, **float**, **String**, **boolean** hoặc **Date**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String |  |

**Trả về:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Trả về hoặc thiết lập thuộc tính tùy chỉnh liên kết với tên được chỉ định. Đọc/ghi Object.

--------------------

Giá trị có thể là **int**, **float**, **String**, **boolean** hoặc **Date**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Lấy một giá trị boolean có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy |
| value | boolean[] | Giá trị thuộc tính tùy chỉnh |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Lấy một giá trị integer có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy |
| value | int[] | Giá trị thuộc tính tùy chỉnh |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Lấy một giá trị DateTime có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy |
| value | java.util.Date[] | Giá trị thuộc tính tùy chỉnh |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Lấy một giá trị string có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy |
| value | java.lang.String[] | Giá trị thuộc tính tùy chỉnh |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Lấy một giá trị float có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy |
| value | float[] | Giá trị thuộc tính tùy chỉnh |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Lấy một giá trị double có tên từ các thuộc tính tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần lấy. |
| value | double[] | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Thiết lập một thuộc tính tùy chỉnh kiểu boolean có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần thiết lập |
| value | boolean | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Thiết lập một thuộc tính tùy chỉnh kiểu integer có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần thiết lập |
| value | int | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Thiết lập một thuộc tính tùy chỉnh kiểu DateTime có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần thiết lập |
| value | java.util.Date | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Thiết lập một thuộc tính tùy chỉnh kiểu string có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần thiết lập |
| value | java.lang.String | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Thiết lập một thuộc tính tùy chỉnh kiểu float có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần thiết lập |
| value | float | Giá trị thuộc tính tùy chỉnh |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Thiết lập một thuộc tính tùy chỉnh kiểu double có tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính tùy chỉnh cần thiết lập |
| value | double | Giá trị thuộc tính tùy chỉnh |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Xóa tất cả các thuộc tính tùy chỉnh.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Lấy một mảng các nhãn nhạy cảm từ các thuộc tính tài liệu tùy chỉnh (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Lấy nhãn nhạy cảm từ các thuộc tính tài liệu tùy chỉnh
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Thêm nhãn vào bộ sưu tập
>          // Ở đây bạn có thể thêm kiểm tra tính hợp lệ của thông tin nhãn (nhãn có sẵn, v.v.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public {
}\n
```

Xóa và đặt lại giá trị mặc định cho tất cả các thuộc tính builtIn.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Chỉ ra chế độ hiển thị của ảnh thu nhỏ tài liệu. Đặt phần tử này thành **true** để bật việc co thu nhỏ ảnh thu nhỏ tài liệu cho hiển thị. Đặt phần tử này thành **false** để bật việc cắt ảnh thu nhỏ tài liệu để chỉ hiển thị các phần phù hợp với màn hình. Đọc/ghi boolean.

**Trả về:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Chỉ ra chế độ hiển thị của ảnh thu nhỏ tài liệu. Đặt phần tử này thành **true** để bật việc co thu nhỏ ảnh thu nhỏ tài liệu cho hiển thị. Đặt phần tử này thành **false** để bật việc cắt ảnh thu nhỏ tài liệu để chỉ hiển thị các phần phù hợp với màn hình. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Chỉ ra liệu các siêu liên kết trong tài liệu có cập nhật hay không. Đặt phần tử này thành **true** để chỉ ra rằng các siêu liên kết đã được cập nhật. Đặt phần tử này thành **false** để chỉ ra rằng các siêu liên kết đã lỗi thời. Đọc/ghi boolean.

**Trả về:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Chỉ ra liệu các siêu liên kết trong tài liệu có cập nhật hay không. Đặt phần tử này thành **true** để chỉ ra rằng các siêu liên kết đã được cập nhật. Đặt phần tử này thành **false** để chỉ ra rằng các siêu liên kết đã lỗi thời. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được cập nhật độc quyền trong phần này bởi một nhà sản xuất. Nhà sản xuất tiếp theo mở tài liệu này sẽ cập nhật các quan hệ siêu liên kết với các siêu liên kết mới được chỉ định trong phần này. Đọc/ghi boolean.

**Trả về:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được cập nhật độc quyền trong phần này bởi một nhà sản xuất. Nhà sản xuất tiếp theo mở tài liệu này sẽ cập nhật các quan hệ siêu liên kết với các siêu liên kết mới được chỉ định trong phần này. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Trả về tổng số slide trong tài liệu bản trình chiếu. Chỉ đọc int.

**Trả về:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Trả về số slide ẩn trong tài liệu bản trình chiếu. Chỉ đọc int.

**Trả về:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Trả về số slide trong bản trình chiếu có ghi chú. Chỉ đọc int.

**Trả về:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Trả về tổng số đoạn được tìm thấy trong tài liệu nếu áp dụng. Chỉ đọc int.

**Trả về:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Trả về tổng số từ trong tài liệu. Chỉ đọc int.

**Trả về:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Trả về tổng số đoạn âm thanh hoặc video có trong tài liệu. Chỉ đọc int.

**Trả về:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Chỉ định tiêu đề của mỗi phần tài liệu. Các phần này không phải là phần tài liệu mà là các biểu diễn khái niệm của các phần tài liệu. Chỉ đọc String[].

**Trả về:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Chỉ ra cách nhóm các phần tài liệu và số lượng phần trong mỗi nhóm. Chỉ đọc IHeadingPair[].

**Trả về:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Sao chép đối tượng hiện tại

**Trả về:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Sao chép đối tượng hiện tại

**Trả về:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone