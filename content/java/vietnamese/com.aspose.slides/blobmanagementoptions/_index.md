---
title: BlobManagementOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho các tùy chọn có thể được sử dụng để quản lý các quy tắc xử lý BLOB và các cài đặt BLOB khác.
type: docs
url: /vi/com.aspose.slides/blobmanagementoptions/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Đại diện cho các tùy chọn có thể được sử dụng để quản lý các quy tắc xử lý BLOB và các thiết lập BLOB khác.
## Hàm tạo

| Constructor | Mô tả |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Tạo các tùy chọn quản lý blob mặc định mới. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là người sở hữu nguồn - tệp hoặc luồng trong suốt vòng đời của thể hiện hay không. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là người sở hữu nguồn - tệp hoặc luồng trong suốt vòng đời của thể hiện hay không. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Thuộc tính này xác định liệu có thể tạo các tệp tạm thời khi làm việc với BLOB hay không, điều này giảm đáng kể việc tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Thuộc tính này xác định liệu có thể tạo các tệp tạm thời khi làm việc với BLOB hay không, điều này giảm đáng kể việc tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Xác định kích thước tối đa tổng cộng (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Xác định kích thước tối đa tổng cộng (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Tạo các tùy chọn quản lý blob mặc định mới.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là người sở hữu nguồn - tệp hoặc luồng trong suốt vòng đời của thể hiện hay không. Nếu thể hiện là người sở hữu, nó sẽ khóa nguồn. Điều này giúp cải thiện việc tiêu thụ bộ nhớ và hiệu năng khi làm việc với BLOB, nhưng nguồn (luồng hoặc tệp) không thể thay đổi trong suốt vòng đời của Presentation.

**Trả về:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là người sở hữu nguồn - tệp hoặc luồng trong suốt vòng đời của thể hiện hay không. Nếu thể hiện là người sở hữu, nó sẽ khóa nguồn. Điều này giúp cải thiện việc tiêu thụ bộ nhớ và hiệu năng khi làm việc với BLOB, nhưng nguồn (luồng hoặc tệp) không thể thay đổi trong suốt vòng đời của Presentation.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Thuộc tính này xác định liệu có thể tạo các tệp tạm thời khi làm việc với BLOB hay không, điều này giảm đáng kể việc tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp.

--------------------

Tất cả các tệp sẽ được xóa sau khi công việc với bản trình chiếu hoàn thành.

**Trả về:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Thuộc tính này xác định liệu có thể tạo các tệp tạm thời khi làm việc với BLOB hay không, điều này giảm đáng kể việc tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp.

--------------------

Tất cả các tệp sẽ được xóa sau khi công việc với bản trình chiếu hoàn thành.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. Thư mục tạm hệ thống sẽ được sử dụng theo mặc định. Quy trình lưu trữ cần có quyền tạo tệp và thư mục tại đó.

**Trả về:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. Thư mục tạm hệ thống sẽ được sử dụng theo mặc định. Quy trình lưu trữ cần có quyền tạo tệp và thư mục tại đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Xác định kích thước tối đa tổng cộng (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Mặc định, tất cả các BLOB được tải vào bộ nhớ; chỉ khi đạt đến giới hạn này thì các cơ chế thay thế (như tệp tạm thời) mới được sử dụng. Giữ BLOB trong bộ nhớ tối đa hoá hiệu năng nhưng có thể gây tiêu thụ bộ nhớ cao. Sử dụng thuộc tính này để điều chỉnh hành vi cho môi trường hoặc yêu cầu của bạn.

--------------------

Thuộc tính này sẽ bị bỏ qua nếu \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) được đặt thành false, vì bộ nhớ sẽ là vị trí lưu trữ duy nhất có sẵn và việc giới hạn việc sử dụng BLOB trong bộ nhớ sẽ không có hiệu lực.

--------------------

Giá trị mặc định là 629.145.600 byte (600 MB).

--------------------

Bạn có thể đặt thuộc tính này về zero, nhưng một lượng bộ nhớ tối thiểu nhỏ vẫn sẽ được dự trữ.

**Trả về:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Xác định kích thước tối đa tổng cộng (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Mặc định, tất cả các BLOB được tải vào bộ nhớ; chỉ khi đạt đến giới hạn này thì các cơ chế thay thế (như tệp tạm thời) mới được sử dụng. Giữ BLOB trong bộ nhớ tối đa hoá hiệu năng nhưng có thể gây tiêu thụ bộ nhớ cao. Sử dụng thuộc tính này để điều chỉnh hành vi cho môi trường hoặc yêu cầu của bạn.

--------------------

Thuộc tính này sẽ bị bỏ qua nếu \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) được đặt thành false, vì bộ nhớ sẽ là vị trí lưu trữ duy nhất có sẵn và việc giới hạn việc sử dụng BLOB trong bộ nhớ sẽ không có hiệu lực.

--------------------

Giá trị mặc định là 629.145.600 byte (600 MB).

--------------------

Bạn có thể đặt thuộc tính này về zero, nhưng một lượng bộ nhớ tối thiểu nhỏ vẫn sẽ được dự trữ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |