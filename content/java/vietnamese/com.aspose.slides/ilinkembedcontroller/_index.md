---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /vi/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Giao diện callback được sử dụng để xác định cách đối tượng nên được xử lý trong quá trình lưu.
## Phương thức

| Method | Description |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Xác định nơi đối tượng nên được lưu trữ. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Trả về một URL tới đối tượng bên ngoài. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Lưu đối tượng bên ngoài. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

Xác định nơi đối tượng nên được lưu trữ. Phương thức này được gọi một lần cho mỗi id đối tượng. Không có bảo đảm rằng sẽ không có hai đối tượng có cùng dữ liệu, semanticName và contentType nhưng có id khác nhau.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| id | int | Id của đối tượng. Id này là duy nhất trong toàn bộ quá trình lưu. |
| entityData | byte[] | Dữ liệu nhị phân của đối tượng. Tham số này có thể null, nếu dữ liệu nhị phân của đối tượng chưa được tạo. |
| semanticName | java.lang.String | Văn bản ngắn mô tả nghĩa của đối tượng. Controller có thể sử dụng nó như một phần của tên đối tượng bên ngoài, nhưng việc đảm bảo các tên là duy nhất và chỉ chứa các ký tự được phép thuộc về dispatcher. |
| contentType | java.lang.String | Kiểu MIME của đối tượng. |
| recomendedExtension | java.lang.String | Phần mở rộng tên tập tin, được khuyến nghị cho kiểu MIME này. |

**Trả về:**
int - Quyết định

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

Trả về một URL tới đối tượng bên ngoài. Phương thức này luôn được gọi nếu \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) trả về [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) và có thể được gọi nếu \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) trả về [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) nhưng không thể nhúng. Có thể được gọi nhiều lần cho cùng một id đối tượng.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| id | int | Id của đối tượng. Id này là duy nhất trong toàn bộ quá trình lưu. |
| referrer | int | Id của đối tượng tham chiếu hoặc 0, nếu đối tượng được tham chiếu bởi tài liệu gốc. Có thể được sử dụng để tạo liên kết tương đối. |

**Trả về:**
java.lang.String - URL của đối tượng bên ngoài hoặc null nếu đối tượng này nên bị bỏ qua.

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

Lưu đối tượng bên ngoài.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| id | int | Id của đối tượng. Id này là duy nhất trong toàn bộ quá trình lưu. |
| entityData | byte[] | Dữ liệu nhị phân của đối tượng. Tham số này không thể null. |