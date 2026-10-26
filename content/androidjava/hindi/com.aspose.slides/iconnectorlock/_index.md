---
title: IConnectorLock
second_title: Java API रेफ़रेंस के माध्यम से Aspose.Slides for Android
description: निर्धारित करता है कि पैरेंट कनेक्टर पर कौन-से ऑपरेशन्स निष्क्रिय हैं।
type: docs
url: /hi/com.aspose.slides/iconnectorlock/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IConnectorLock extends IBaseShapeLock
```

निर्धारित करता है कि कौन-सी ऑपरेशन्स पैरेंट कनेक्टर पर निष्क्रिय हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | निर्धारित करता है कि इस आकृति को समूह में जोड़ना निषिद्ध है या नहीं। |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | निर्धारित करता है कि इस आकृति को समूह में जोड़ना निषिद्ध है या नहीं। |
| [getSelectLocked()](#getSelectLocked--) | निर्धारित करता है कि इस आकृति का चयन करना निषिद्ध है या नहीं। |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | निर्धारित करता है कि इस आकृति का चयन करना निषिद्ध है या नहीं। |
| [getRotateLocked()](#getRotateLocked--) | निर्धारित करता है कि इस आकृति का घूर्णन कोण बदलना निषिद्ध है या नहीं। |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | निर्धारित करता है कि इस आकृति का घूर्णन कोण बदलना निषिद्ध है या नहीं। |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | निर्धारित करता है कि आकार बदलते समय आकृति को अनुपात संरक्षित रखना चाहिए या नहीं। |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | निर्धारित करता है कि आकार बदलते समय आकृति को अनुपात संरक्षित रखना चाहिए या नहीं। |
| [getPositionMove()](#getPositionMove--) | निर्धारित करता है कि इस आकृति को स्थानांतरित करना निषिद्ध है या नहीं। |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | निर्धारित करता है कि इस आकृति को स्थानांतरित करना निषिद्ध है या नहीं। |
| [getSizeLocked()](#getSizeLocked--) | निर्धारित करता है कि इस आकृति का आकार बदलना निषिद्ध है या नहीं। |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | निर्धारित करता है कि इस आकृति का आकार बदलना निषिद्ध है या नहीं। |
| [getEditPointsLocked()](#getEditPointsLocked--) | निर्धारित करता है कि इस आकृति की रूपरेखा को सीधे बदलना निषिद्ध है या नहीं। |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | निर्धारित करता है कि इस आकृति की रूपरेखा को सीधे बदलना निषिद्ध है या नहीं। |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | निर्धारित करता है कि समायोजन मानों को बदलना निषिद्ध है या नहीं। |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | निर्धारित करता है कि समायोजन मानों को बदलना निषिद्ध है या नहीं। |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | निर्धारित करता है कि तीर सिरों को बदलना निषिद्ध है या नहीं। |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | निर्धारित करता है कि तीर सिरों को बदलना निषिद्ध है या नहीं। |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | निर्धारित करता है कि आकृति प्रकार को बदलना निषिद्ध है या नहीं। |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | निर्धारित करता है कि आकृति प्रकार को बदलना निषिद्ध है या नहीं। |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

निर्धारित करता है कि इस आकृति को समूह में जोड़ना निषिद्ध है या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

निर्धारित करता है कि इस आकृति को समूह में जोड़ना निषिद्ध है या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

निर्धारित करता है कि इस आकृति का चयन करना निषिद्ध है या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

निर्धारित करता है कि इस आकृति का चयन करना निषिद्ध है या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

निर्धारित करता है कि इस आकृति का घूर्णन कोण बदलना निषिद्ध है या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

निर्धारित करता है कि इस आकृति का घूर्णन कोण बदलना निषिद्ध है या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

निर्धारित करता है कि आकार बदलते समय आकृति को अनुपात संरक्षित रखना चाहिए या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

निर्धारित करता है कि आकार बदलते समय आकृति को अनुपात संरक्षित रखना चाहिए या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getPositionMove() {#getPositionMove--}
```
public abstract boolean getPositionMove()
```

निर्धारित करता है कि इस आकृति को स्थानांतरित करना निषिद्ध है या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public abstract void setPositionMove(boolean value)
```

निर्धारित करता है कि इस आकृति को स्थानांतरित करना निषिद्ध है या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

निर्धारित करता है कि इस आकृति का आकार बदलना निषिद्ध है या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

निर्धारित करता है कि इस आकृति का आकार बदलना निषिद्ध है या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

निर्धारित करता है कि इस आकृति की रूपरेखा को सीधे बदलना निषिद्ध है या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

निर्धारित करता है कि इस आकृति की रूपरेखा को सीधे बदलना निषिद्ध है या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

निर्धारित करता है कि समायोजन मानों को बदलना निषिद्ध है या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

निर्धारित करता है कि समायोजन मानों को बदलना निषिद्ध है या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

निर्धारित करता है कि तीर सिरों को बदलना निषद्ध है या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

निर्धारित करता है कि तीर सिरों को बदलना निषद्ध है या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

निर्धारित करता है कि आकृति प्रकार को बदलना निषिद्ध है या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

निर्धारित करता है कि आकृति प्रकार को बदलना निषिद्ध है या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |