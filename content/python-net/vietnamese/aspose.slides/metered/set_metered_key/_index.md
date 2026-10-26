---
title: set_metered_key method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Thiết lập khóa công khai và khóa riêng tư có công tơ.
Nếu bạn mua giấy phép có công tơ, khi khởi động ứng dụng, API này nên được gọi; thường thì điều này là đủ.
Tuy nhiên, nếu luôn thất bại khi tải dữ liệu tiêu thụ và vượt quá 24 giờ, giấy phép sẽ chuyển sang trạng thái đánh giá.
Để tránh trường hợp này, bạn nên thường xuyên kiểm tra trạng thái giấy phép; nếu nó ở trạng thái đánh giá, gọi lại API này.

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| public_key | **str** | public key |
| private_key | **str** | private key |

### Xem Thêm
* lớp [`Metered`](/slides/python-net/vi/aspose.slides/metered)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)