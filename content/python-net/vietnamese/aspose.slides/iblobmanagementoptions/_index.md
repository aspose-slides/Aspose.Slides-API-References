---
title: IBlobManagementOptions class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions lớp

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an 
            audio, video or presentation itself. A number of techniques are used to optimize memory consumption 
            while working with BLOBs - which was already stored in the presentation or be added later programmatically. 
            Using [`IBlobManagementOptions`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions) you can change a different behavior aspects regarding BLOBs 
            handling for the [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation) instance lifetime.

The IBlobManagementOptions type exposes the following members:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của nguồn - tệp <br/>            hoặc luồng trong suốt thời gian tồn tại của thể hiện hay không. Nếu thể hiện là chủ sở hữu, nó sẽ khóa nguồn. Điều này giúp <br/>            cải thiện việc tiêu thụ bộ nhớ và hiệu năng khi làm việc với BLOBs, nhưng nguồn (luồng hoặc tệp) <br/>            không thể thay đổi trong suốt thời gian tồn tại của thể hiện Presentation. Đây là một ví dụ: |
| [`is_temporary_files_allowed`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Thuộc tính này xác định liệu có thể tạo tệp tạm thời khi làm việc với BLOBs hay không, điều này giảm đáng kể <br/>            việc tiêu thụ bộ nhớ nhưng yêu cầu quyền tạo tệp.<br/>            Tất cả các tệp sẽ bị xóa sau khi công việc với bản trình chiếu hoàn thành. |
| [`temp_files_root_path`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. Thư mục tạm thời của hệ thống sẽ được sử dụng mặc định. <br/>            Quá trình lưu trữ cần có quyền <br/>            tạo tệp và thư mục tại đó. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Mặc định, tất cả BLOB<br/>            được tải vào bộ nhớ; chỉ khi đạt đến giới hạn này thì các cơ chế thay thế (như tệp tạm thời)<br/>            mới được áp dụng. Giữ BLOB trong bộ nhớ tối đa hoá hiệu năng nhưng có thể gây sử dụng bộ nhớ cao. Sử dụng<br/>            thuộc tính này để điều chỉnh hành vi phù hợp với môi trường hoặc yêu cầu của bạn. |

### Xem thêm
* lớp [`IBlobManagementOptions`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions)
* lớp [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)