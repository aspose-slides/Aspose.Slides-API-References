---
title: Metered
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Cung cấp các phương thức để thiết lập khóa metered.
type: docs
url: /vi/com.aspose.slides/metered/
---
**Kế thừa:**
java.lang.Object
```
public class Metered
```

Cung cấp các phương thức để thiết lập khóa metered.
## Phương thức khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [Metered()](#Metered--) | Khởi tạo một thể hiện mới của lớp này. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Thiết lập khóa công cộng và riêng tư cho metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Lấy kích thước tệp tiêu thụ |
| [getConsumptionCredit()](#getConsumptionCredit--) | Lấy tín dụng tiêu thụ |
| [isMeteredLicensed()](#isMeteredLicensed--) | Kiểm tra xem metered có được cấp phép hay không |
### Metered() {#Metered--}
```
public Metered()
```


Khởi tạo một thể hiện mới của lớp này.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Thiết lập khóa công cộng và riêng tư cho metered. Nếu bạn mua giấy phép metered, khi khởi động ứng dụng, API này nên được gọi, thường thì điều này là đủ. Tuy nhiên, nếu luôn thất bại trong việc tải dữ liệu tiêu thụ và vượt quá 24 giờ, giấy phép sẽ được đặt ở trạng thái đánh giá, để tránh trường hợp này, bạn nên thường xuyên kiểm tra trạng thái giấy phép, nếu nó ở trạng thái đánh giá, hãy gọi lại API này.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| publicKey | java.lang.String | khóa công cộng |
| privateKey | java.lang.String | khóa riêng tư |

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


Kiểm tra xem metered có được cấp phép hay không

**Giá trị trả về:**
boolean - Đúng hoặc Sai