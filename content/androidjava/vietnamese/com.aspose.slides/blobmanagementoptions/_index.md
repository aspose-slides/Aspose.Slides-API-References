---
title: BlobManagementOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu thị các tùy chọn có thể được sử dụng để quản lý các quy tắc xử lý BLOB và các thiết lập BLOB khác.
type: docs
url: /vi/com.aspose.slides/blobmanagementoptions/
---
**Kế thừa:**  
java.lang.Object

**Tất cả các giao diện được triển khai:**  
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)  
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Biểu thị các tùy chọn có thể được sử dụng để quản lý quy tắc xử lý BLOB và các cài đặt BLOB khác.

## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Tạo các tùy chọn quản lý blob mặc định mới. |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của tệp hoặc luồng nguồn trong suốt thời gian sống của thể hiện hay không. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của tệp hoặc luồng nguồn trong suốt thời gian sống của thể hiện hay không. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Thuộc tính này xác định liệu các tệp tạm thời có thể được tạo ra khi làm việc với BLOBs, điều này giảm đáng kể mức tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Thuộc tính này xác định liệu các tệp tạm thời có thể được tạo ra khi làm việc với BLOBs, điều này giảm đáng kể mức tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Tạo các tùy chọn quản lý blob mặc định mới.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của tệp hoặc luồng nguồn trong suốt thời gian sống của thể hiện hay không. Nếu thể hiện là chủ sở hữu, nó sẽ khóa nguồn. Điều này giúp cải thiện mức tiêu thụ bộ nhớ và hiệu năng khi làm việc với BLOBs, nhưng nguồn (luồng hoặc tệp) không thể thay đổi trong suốt thời gian sống của thể hiện Presentation.

**Trả về:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của tệp hoặc luồng nguồn trong suốt thời gian sống của thể hiện hay không. Nếu thể hiện là chủ sở hữu, nó sẽ khóa nguồn. Điều này giúp cải thiện mức tiêu thụ bộ nhớ và hiệu năng khi làm việc với BLOBs, nhưng nguồn (luồng hoặc tệp) không thể thay đổi trong suốt thời gian sống của thể hiện Presentation.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Thuộc tính này xác định liệu các tệp tạm thời có thể được tạo ra khi làm việc với BLOBs, điều này giảm đáng kể mức tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp.

--------------------

Tất cả các tệp sẽ bị xóa sau khi công việc với bản trình chiếu kết thúc.

**Trả về:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Thuộc tính này xác định liệu các tệp tạm thời có thể được tạo ra khi làm việc với BLOBs, điều này giảm đáng kể mức tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp.

--------------------

Tất cả các tệp sẽ bị xóa sau khi công việc với bản trình chiếu kết thúc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. Thư mục tạm thời của System sẽ được sử dụng theo mặc định. Quá trình lưu trữ cần có quyền tạo tệp và thư mục tại đó.

**Trả về:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. Thư mục tạm thời của System sẽ được sử dụng theo mặc định. Quá trình lưu trữ cần có quyền tạo tệp và thư mục tại đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Theo mặc định, tất cả các BLOB được tải vào bộ nhớ; chỉ khi đạt tới giới hạn này thì các cơ chế thay thế (như tệp tạm thời) mới được sử dụng. Giữ BLOB trong bộ nhớ tối đa hóa hiệu năng nhưng có thể dẫn đến mức tiêu thụ bộ nhớ cao. Sử dụng thuộc tính này để điều chỉnh hành vi cho môi trường hoặc yêu cầu của bạn.

--------------------

Thuộc tính này bị bỏ qua nếu \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) được đặt thành false, vì khi đó bộ nhớ là vị trí lưu trữ duy nhất và việc giới hạn BLOB trong bộ nhớ không có tác dụng.

--------------------

Giá trị mặc định là 629 145 600 byte (600 MB).

--------------------

Bạn có thể đặt thuộc tính này bằng zero, nhưng vẫn sẽ được dự trữ một lượng bộ nhớ tối thiểu nhỏ.

**Trả về:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Theo mặc định, tất cả các BLOB được tải vào bộ nhớ; chỉ khi đạt tới giới hạn này thì các cơ chế thay thế (như tệp tạm thời) mới được sử dụng. Giữ BLOB trong bộ nhớ tối đa hóa hiệu năng nhưng có thể dẫn đến mức tiêu thụ bộ nhớ cao. Sử dụng thuộc tính này để điều chỉnh hành vi cho môi trường hoặc yêu cầu của bạn.

--------------------

Thuộc tính này bị bỏ qua nếu \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) được đặt thành false, vì khi đó bộ nhớ là vị trí lưu trữ duy nhất và việc giới hạn BLOB trong bộ nhớ không có tác dụng.

--------------------

Giá trị mặc định là 629 145 600 byte (600 MB).

--------------------

Bạn có thể đặt thuộc tính này bằng zero, nhưng vẫn sẽ được dự trữ một lượng bộ nhớ tối thiểu nhỏ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |