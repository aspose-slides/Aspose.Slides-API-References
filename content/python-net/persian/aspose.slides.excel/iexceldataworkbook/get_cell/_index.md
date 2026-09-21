---
title: get_cell method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
سلولی را از کاربرگ مشخص‌شده با استفاده از ایندکس آن و نام سلول به سبک Excel (مثال: "B2") بازیابی می‌کند.

### بازگشت
سلول در مکان مشخص‌شده.

```python
def get_cell(self, worksheet_index, cell_name):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| worksheet_index | **int** | ایندکس صفر-محور کاربرگ. |
| cell_name | **str** | مرجع سلول به سبک Excel (مثال: "A1"، "C5"). |

## get_cell(self, worksheet_name, cell_name) {#str-str}
سلولی را از کاربرگ مشخص‌شده با استفاده از نام سلول به سبک Excel (مثال: "B2") بازیابی می‌کند.

### بازگشت
سلول در مکان مشخص‌شده.

```python
def get_cell(self, worksheet_name, cell_name):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| worksheet_name | **str** | نام کاربرگ. |
| cell_name | **str** | مرجع سلول به سبک Excel (مثال: "A1"، "C5"). |

## get_cell(self, worksheet_index, row, column) {#int-int-int}
سلولی را از کاربرگ مشخص‌شده با استفاده از ایندکس آن و مختصات سلول بازیابی می‌کند.

### بازگشت
سلول در مکان مشخص‌شده.

```python
def get_cell(self, worksheet_index, row, column):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| worksheet_index | **int** | ایندکس صفر-محور کاربرگ. |
| row | **int** | ایندکس صفر-محور سطر سلول. |
| column | **int** | ایندکس صفر-محور ستون سلول. |

## get_cell(self, worksheet_name, row, column) {#str-int-int}
سلولی را از کاربرگ مشخص‌شده با استفاده از نام آن و مختصات سلول بازیابی می‌کند.

### بازگشت
سلول در مکان مشخص‌شده.

```python
def get_cell(self, worksheet_name, row, column):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| worksheet_name | **str** | نام کاربرگ. |
| row | **int** | ایندکس صفر-محور سطر سلول. |
| column | **int** | ایندکس صفر-محور ستون سلول. |

### موارد مرتبط
* کلاس [`IExcelDataCell`](/slides/python-net/fa/aspose.slides.excel/iexceldatacell)
* کلاس [`IExcelDataWorkbook`](/slides/python-net/fa/aspose.slides.excel/iexceldataworkbook)
* ماژول [`aspose.slides.excel`](/slides/python-net/fa/aspose.slides.excel)
* کتابخانه [`Aspose.Slides`](/slides/python-net)