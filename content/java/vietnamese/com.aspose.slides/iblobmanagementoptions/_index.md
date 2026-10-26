---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: Một Binary Large Object (BLOB) là dữ liệu nhị phân được lưu trữ dưới dạng một thực thể duy nhất - tức là.
type: docs
url: /vi/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Một Binary Large Object (BLOB) là dữ liệu nhị phân được lưu trữ dưới dạng một thực thể duy nhất - tức là BLOB có thể là âm thanh, video hoặc chính bản trình chiếu. Một số kỹ thuật được sử dụng để tối ưu tiêu thụ bộ nhớ khi làm việc với BLOBs - đã được lưu trong bản trình chiếu hoặc sẽ được thêm sau này bằng chương trình. Sử dụng [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) bạn có thể thay đổi các khía cạnh hành vi khác nhau liên quan đến việc xử lý BLOBs cho vòng đời của thể hiện [IPresentation](../../com.aspose.slides/ipresentation).

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của nguồn - tệp hoặc luồng trong suốt vòng đời của thể hiện hay không. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của nguồn - tệp hoặc luồng trong suốt vòng đời của thể hiện hay không. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Thuộc tính này xác định liệu các tệp tạm thời có thể được tạo khi làm việc với BLOBs, điều này giảm đáng kể tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Thuộc tính này xác định liệu các tệp tạm thời có thể được tạo khi làm việc với BLOBs, điều này giảm đáng kể tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của nguồn - tệp hoặc luồng trong suốt vòng đời của thể hiện hay không. Nếu thể hiện là chủ sở hữu, nó sẽ khóa nguồn. Điều này giúp cải thiện tiêu thụ bộ nhớ và hiệu suất khi làm việc với BLOBs, nhưng nguồn (luồng hoặc tệp) không thể được thay đổi trong vòng đời của thể hiện Presentation. Đây là một ví dụ:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException sẽ được ném vì pres.pptx bị khóa trong suốt vòng đời của Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // sau khi đối tượng Presentation bị giải phóng, tệp được mở khóa và có thể được xóa
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Trả về:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của nguồn - tệp hoặc luồng trong suốt vòng đời của thể hiện hay không. Nếu thể hiện là chủ sở hữu, nó sẽ khóa nguồn. Điều này giúp cải thiện tiêu thụ bộ nhớ và hiệu suất khi làm việc với BLOBs, nhưng nguồn (luồng hoặc tệp) không thể được thay đổi trong vòng đời của thể hiện Presentation. Đây là một ví dụ:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException sẽ được ném vì pres.pptx bị khóa trong suốt vòng đời của Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // sau khi đối tượng Presentation được giải phóng, tệp được mở khóa và có thể bị xóa
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

Thuộc tính này xác định liệu các tệp tạm thời có thể được tạo khi làm việc với BLOBs, điều này giảm đáng kể tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp.

--------------------

Tất cả các tệp sẽ bị xóa sau khi công việc với bản trình chiếu được hoàn thành.

**Trả về:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Thuộc tính này xác định liệu các tệp tạm thời có thể được tạo khi làm việc với BLOBs, điều này giảm đáng kể tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp.

--------------------

Tất cả các tệp sẽ bị xóa sau khi công việc với bản trình chiếu được hoàn thành.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. Thư mục tạm thời của hệ thống sẽ được sử dụng theo mặc định. Quy trình lưu trữ phải có quyền tạo tệp và thư mục ở đó.

**Trả về:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. Thư mục tạm thời của hệ thống sẽ được sử dụng theo mặc định. Quy trình lưu trữ phải có quyền tạo tệp và thư mục ở đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Mặc định, tất cả các BLOB được tải vào bộ nhớ; chỉ khi đạt giới hạn này thì các cơ chế thay thế (như tệp tạm thời) mới được áp dụng. Giữ BLOB trong bộ nhớ tối đa hiệu suất nhưng có thể dẫn đến mức sử dụng bộ nhớ cao. Sử dụng thuộc tính này để điều chỉnh hành vi phù hợp với môi trường hoặc yêu cầu của bạn.

--------------------

Thuộc tính này bị bỏ qua nếu \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) được đặt thành false, vì khi đó bộ nhớ là nơi lưu trữ duy nhất và việc giới hạn việc sử dụng BLOB trong bộ nhớ không có hiệu lực.

--------------------

Giá trị mặc định là 629.145.600 byte (600 MB).

--------------------

Bạn có thể đặt thuộc tính này thành 0, nhưng một lượng bộ nhớ tối thiểu nhỏ vẫn sẽ được dự trữ.

**Trả về:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Mặc định, tất cả các BLOB được tải vào bộ nhớ; chỉ khi đạt giới hạn này thì các cơ chế thay thế (như tệp tạm thời) mới được áp dụng. Giữ BLOB trong bộ nhớ tối đa hiệu suất nhưng có thể dẫn đến mức sử dụng bộ nhớ cao. Sử dụng thuộc tính này để điều chỉnh hành vi phù hợp với môi trường hoặc yêu cầu của bạn.

--------------------

Thuộc tính này bị bỏ qua nếu \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) được đặt thành false, vì khi đó bộ nhớ là nơi lưu trữ duy nhất và việc giới hạn việc sử dụng BLOB trong bộ nhớ không có hiệu lực.

--------------------

Giá trị mặc định là 629.145.600 byte (600 MB).

--------------------

Bạn có thể đặt thuộc tính này thành 0, nhưng một lượng bộ nhớ tối thiểu nhỏ vẫn sẽ được dự trữ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |