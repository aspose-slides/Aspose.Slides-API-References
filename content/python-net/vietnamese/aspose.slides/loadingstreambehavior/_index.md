---
title: LoadingStreamBehavior enumeration
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior liệt kê

Đối tượng **io.RawIOBase** được truyền vào một phương thức được coi là một Binary Large Object (BLOB) (xem mô tả [`IBlobManagementOptions`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions)). Các giá trị của liệt kê này xác định cách **io.RawIOBase** nên được xử lý khi nó được truyền vào phương thức. Tùy thuộc vào yêu cầu, có thể đưa ra các quyết định khác nhau để cung cấp hành vi hiệu quả nhất.

Kiểu LoadingStreamBehavior cung cấp các thành viên sau:

## Trường

| Trường | Mô tả |
| :- | :- |
| READ_STREAM_AND_RELEASE | Luồng sẽ được đọc tới cuối và sau đó được giải phóng - tức là sẽ được đảm bảo rằng luồng này <br/>            sẽ không được sử dụng bởi thể hiện [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation) trong tương lai. Nó có thể được đóng bởi mã client <br/>            hoặc được sử dụng theo bất kỳ cách nào khác. |
| KEEP_LOCKED | Luồng sẽ bị khóa bên trong đối tượng [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation), tức là quyền sở hữu <br/>            của luồng sẽ được chuyển giao. Đối tượng [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation) sẽ chịu trách nhiệm <br/>            giải phóng đúng cách luồng khi đối tượng này tự nó được giải phóng. <br/>            Hành vi này cực kỳ hữu ích khi bạn cần tuần tự hoá một tệp BLOB lớn (chẳng hạn video <br/>            hoặc audio lớn - xem mô tả [`IBlobManagementOptions`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions)) và muốn ngăn việc tải <br/>            tệp này vào bộ nhớ hoặc các vấn đề hiệu năng khác. Bạn chỉ cần mở **System.IO.FileStream** <br/>            cho tệp này và truyền vào một phương thức, chọn [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/vi/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |


### Xem thêm
* lớp [`IBlobManagementOptions`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions)
* lớp [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)