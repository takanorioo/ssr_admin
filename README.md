###ssr_admin

SSR調査研究 管理者用サンプルアプリケーション

###概要

SSR調査研究 管理者用サンプルアプリケーション


### 設計

* アクター

>1. 管理者(大学)
>1. 修了学生
>1. 在学生
>1. 非学生



* [ユースケース図](https://github.com/mixi-inc/iOSTraining/wiki/1.1-Objective-C-%E3%81%AE%E5%9F%BA%E7%A4%8E)
* [ユースケース記述](https://github.com/mixi-inc/iOSTraining/wiki/1.1-Objective-C-%E3%81%AE%E5%9F%BA%E7%A4%8E)
* [DB設計](https://github.com/mixi-inc/iOSTraining/wiki/1.1-Objective-C-%E3%81%AE%E5%9F%BA%E7%A4%8E)


### アプリケーション構成

>#####管理者用アプリケーション
>* 管理者用EmailとPASSで認証
>* 全てのユースケースが可能
>
>#####在学生と修了学生用アプリケーション
>* 学内EmailとPASSで認証
>
>##### 非学生と在学生用アプリケーション
>* EmailとPASSで認証 
>* 説明会関連のユースケースを行う。


### 各ルーティングとその説明


>[[管理者用アプリケーション]]
>
>[[在学生と修了学生用アプリケーション]]
>
>[[在学生と非学生用アプリケーション]]
