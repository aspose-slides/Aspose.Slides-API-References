---
title: Metered
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp các phương thức để thiết lập khóa có công tơ.
type: docs
url: /vi/com.aspose.slides/metered/
---
**Kế thừa:**
java.lang.Object
```
public class Metered
```

Cung cấp các phương thức để thiết lập khóa có công tơ.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [Metered()](#Metered--) | Khởi tạo một thể hiện mới của lớp này. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Thiết lập khóa công cộng và khóa riêng có công tơ. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Lấy kích thước tệp tiêu thụ |
| [getConsumptionCredit()](#getConsumptionCredit--) | Lấy tín dụng tiêu thụ |
| [isMeteredLicensed()](#isMeteredLicensed--) | Kiểm tra xem có công tơ đã được cấp phép hay không |
### Metered() {#Metered--}
```
public Metered()
```

Khởi tạo một thể hiện mới của lớp này.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Thiết lập khóa công cộng và khóa riêng có công tơ. Nếu bạn mua giấy phép có công tơ, khi khởi động ứng dụng, API này nên được gọi, thường thì đủ. Tuy nhiên, nếu luôn thất bại trong việc tải lên dữ liệu tiêu thụ và vượt quá 24 giờ, giấy phép sẽ được đặt ở trạng thái đánh giá; để tránh trường hợp này, bạn nên kiểm tra trạng thái giấy phép thường xuyên, nếu nó ở trạng thái đánh giá, hãy gọi lại API này.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| publicKey | java.lang.String | khóa công cộng |
| privateKey | java.lang.String | khóa riêng |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

Lấy kích thước tệp tiêu thụ

**Giá trị trả về:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

Lấy tín dụng tiêu thụ

**Giá trị trả về:**
double - lượng tiêu thụ
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

Kiểm tra xem có công tơ đã được cấp phép hay không

**Giá trị trả về:**
boolean - True hoặc false