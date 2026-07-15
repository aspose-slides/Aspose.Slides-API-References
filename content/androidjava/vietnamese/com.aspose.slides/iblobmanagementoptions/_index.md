---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Một Đối tượng Nhị phân Lớn (BLOB) là dữ liệu nhị phân được lưu trữ dưới dạng một thực thể duy nhất - ví dụ.
type: docs
url: /vi/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Một Đối tượng Nhị phân Lớn (BLOB) là dữ liệu nhị phân được lưu trữ dưới dạng một thực thể duy nhất - ví dụ BLOB có thể là âm thanh, video hoặc bản trình chiếu tự nó. Một số kỹ thuật được sử dụng để tối ưu hóa việc tiêu thụ bộ nhớ khi làm việc với BLOB - đã được lưu trong bản trình chiếu hoặc sẽ được thêm sau này một cách lập trình. Sử dụng [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) bạn có thể thay đổi các khía cạnh hành vi khác nhau liên quan đến việc xử lý BLOB cho vòng đời của thể hiện [IPresentation](../../com.aspose.slides/ipresentation).

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | The root path where temporary files will be created. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | The root path where temporary files will be created. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của nguồn - tệp hoặc luồng trong suốt thời gian tồn tại của thể hiện hay không. Nếu thể hiện là chủ sở hữu, nó sẽ khóa nguồn. Điều này giúp cải thiện việc tiêu thụ bộ nhớ và hiệu năng khi làm việc với BLOB, nhưng nguồn (luồng hoặc tệp) không thể được thay đổi trong suốt thời gian tồn tại của thể hiện Presentation. Đây là một ví dụ:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException sẽ được ném vì pres.pptx bị khóa trong suốt thời gian tồn tại của Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // sau khi đối tượng Presentation được giải phóng, tệp sẽ được mở khóa và có thể bị xóa
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
>  ```


**Trả về:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của nguồn - tệp hoặc luồng trong suốt thời gian tồn tại của thể hiện hay không. Nếu thể hiện là chủ sở hữu, nó sẽ khóa nguồn. Điều này giúp cải thiện việc tiêu thụ bộ nhớ và hiệu năng khi làm việc với BLOB, nhưng nguồn (luồng hoặc tệp) không thể được thay đổi trong suốt thời gian tồn tại của thể hiện Presentation. Đây là một ví dụ:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException sẽ được ném vì pres.pptx bị khóa trong suốt thời gian tồn tại của Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // sau khi đối tượng Presentation được giải phóng, tệp sẽ được mở khóa và có thể bị xóa
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Thuộc tính này xác định liệu có thể tạo các tệp tạm thời khi làm việc với BLOB hay không, điều này giảm đáng kể việc tiêu thụ bộ nhớ nhưng yêu cầu quyền để tạo tệp.

--------------------

Tất cả các tệp sẽ được xóa sau khi công việc với bản trình chiếu hoàn tất.

**Trả về:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Thuộc tính này xác định liệu có thể tạo các tệp tạm thời khi làm việc với BLOB hay không, điều này giảm đáng kể việc tiêu thụ bộ nhớ nhưng yêu cầu quyền để tạo tệp.

--------------------

Tất cả các tệp sẽ được xóa sau khi công việc với bản trình chiếu hoàn tất.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. Thư mục tạm thời hệ thống sẽ được sử dụng theo mặc định. Quá trình lưu trữ phải có quyền tạo tệp và thư mục ở đó.

**Trả về:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. Thư mục tạm thời hệ thống sẽ được sử dụng theo mặc định. Quá trình lưu trữ phải có quyền tạo tệp và thư mục ở đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Mặc định, tất cả các BLOB được tải vào bộ nhớ; chỉ khi đạt tới giới hạn này thì các cơ chế thay thế (như tệp tạm thời) mới được sử dụng. Giữ BLOB trong bộ nhớ tối đa hóa hiệu năng nhưng có thể dẫn đến việc sử dụng bộ nhớ cao. Sử dụng thuộc tính này để điều chỉnh hành vi phù hợp với môi trường hoặc yêu cầu của bạn.

--------------------

Thuộc tính này bị bỏ qua nếu \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) được đặt thành false, vì khi đó bộ nhớ là vị trí lưu trữ duy nhất có sẵn và việc giới hạn việc sử dụng BLOB trong bộ nhớ không có tác dụng.

--------------------

Giá trị mặc định là 629.145.600 byte (600 MB).

--------------------

Bạn có thể đặt thuộc tính này thành zero, nhưng một lượng bộ nhớ tối thiểu nhỏ vẫn sẽ được dự trữ.

**Trả về:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Mặc định, tất cả các BLOB được tải vào bộ nhớ; chỉ khi đạt tới giới hạn này thì các cơ chế thay thế (như tệp tạm thời) mới được sử dụng. Giữ BLOB trong bộ nhớ tối đa hóa hiệu năng nhưng có thể dẫn đến việc sử dụng bộ nhớ cao. Sử dụng thuộc tính này để điều chỉnh hành vi phù hợp với môi trường hoặc yêu cầu của bạn.

--------------------

Thuộc tính này bị bỏ qua nếu \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) được đặt thành false, vì khi đó bộ nhớ là vị trí lưu trữ duy nhất có sẵn và việc giới hạn việc sử dụng BLOB trong bộ nhớ không có tác dụng.

--------------------

Giá trị mặc định là 629.145.600 byte (600 MB).

--------------------

Bạn có thể đặt thuộc tính này thành zero, nhưng một lượng bộ nhớ tối thiểu nhỏ vẫn sẽ được dự trữ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |