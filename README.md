# AI-in-Angular

<img width="1008" height="174" alt="image" src="https://github.com/user-attachments/assets/20b5182b-e812-4cf9-950b-20babb593a95" />


   <h2 dir="rtl">1. Agents.md</h2>


یک فایل استاندارد به اسم AGENTS.md داخل پروژه

کاربرد:

تعریف قوانین کلی پروژه برای همه AIها

مثل:
<li dir="rtl">ساختار پروژه</li>
<li dir="rtl">naming convention</li>
<li dir="rtl">اینکه Angular Standalone استفاده می‌کنی یا Module-based</li>
<li dir="rtl">preferenceها (Signals، RxJS، OnPush، etc)</li>

```ts
- Use Angular Signals
- Prefer standalone components
- Avoid any type
- Use OnPush change detection

```


<h2 dir="rtl">2. Claude (Anthropic)</h2>
<div dir="rtl">Claude Code یک ابزار هوش مصنوعی از Anthropic هست که می‌تونی موقع ساخت پروژه جدید انگولاری ازش استفاده کنی تا کدهای اولیه، کامپوننت‌ها و حتی تست‌ها رو سریع‌تر و مطابق با استانداردهای مدرن انگولار تولید کنه.</div>
</br>
<div dir="rtl">تنظیم کانتکست مخصوص Claude AI</div>
<div dir="rtl">به Claude می‌گه:</div>

<li dir="rtl">این پروژه Angularه</li>
<li dir="rtl">Best Practiceهای Angular چیه</li>
<li dir="rtl">چطور کد تولید کنه (Service, Component, Signal, etc)</li>


-----------------------------------------------------------------------------

<h2>راهنمای جامع LLM در Angular (از صفر تا صد)</h2>

<div dir="rtl">LLM اصلاً چیه؟</div>

<div dir="rtl">LLM (Large Language Model)
مدل‌های زبانی بزرگی هستن که می‌تونن:
</div>

<li dir="rtl">کد بنویسن</li>
<li dir="rtl">کد رو بفهمن</li>
<li dir="rtl">ریفکتور کنن</li>
<li dir="rtl">تست بنویسن</li>
<li dir="rtl">توضیح بدن</li>
<li dir="rtl">Context پروژه رو تحلیل کنن</li>

<h2 dir="rtl"> LLM توی Angular دقیقاً کجا به کارت میاد؟</h2>

| بخش          | کاربرد LLM                          |
| ------------ | ----------------------------------- |
| Component    | ساخت، ریفکتور، توضیح logic          |
| Service      | نوشتن API layer، caching، state     |
| Pipe         | نام‌گذاری بهتر، ساده‌سازی transform |
| Unit Test    | ساخت Test کامل و Edge Case          |
| Refactor     | شکستن کامپوننت‌های بزرگ             |
| Architecture | پیشنهاد ساختار پوشه                 |
| Bug Fix      | تحلیل باگ‌های عجیب                  |
| Performance  | تشخیص Bottleneck                    |
| DX           | بهتر شدن تجربه توسعه                |
