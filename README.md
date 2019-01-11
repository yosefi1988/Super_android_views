# Super_android_views

A library for edittext that controls the input values
In the original version it will only support Persian languages

creator sajjad yosefi 09123678522


برای استفاده از این کتابخانه فایل زیر را به پروژه تون اضافه کنید 
https://github.com/yosefi1988/Super_android_views/blob/master/superandroidcomponents-Library/superandroidcomponents-release.aar

![alt text](https://raw.githubusercontent.com/yosefi1988/Super_android_views/master/app/src/main/res/drawable/1.png)

بعد از اضافه کردن در 
dependency
های پروژه تون ماژول را اضافه کنید


سپس به راحتی از کامپوننت های اضافه شده استفاده کنید و خروجی زیر را ببینید

در صفت اضافه شده می توانید انواع زیر را داشته باشید

app:modeI="amount"
برای مقادیری که به ریال قرار است دریافت شود از این نوع استفاده کنید

app:modeI="number"
جاهایی که قرار است فقط عدد وارد شود مانند سن فرد

app:modeI="text" 
متن معمولی

app:modeI="card" 
جایی که کاربر میخواهد شماره کارت بانکی وارد کند

app:modeI="mobile" 
شماره موبایل


app:modeI="sheba" 
هر جایی که کاربر می خواهد شماره شبا ی حساب بانکی خود را وارد کند

app:modeI="password_text"
جایی که کاربر میخواهد رمز به صورت متنی وارد کند

app:modeI="password_number"
جایی که کاربر رمزی را فقط باید با عدد وارد کند

برای مثال 
    <ir.sajjadyosefi.superandroidcomponents.SuperEditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="20dp"
        app:modeI="password_number" />

![alt text](https://raw.githubusercontent.com/yosefi1988/Super_android_views/master/app/src/main/res/drawable/2.png)


![alt text](https://raw.githubusercontent.com/yosefi1988/Super_android_views/master/app/src/main/res/drawable/3.png)

