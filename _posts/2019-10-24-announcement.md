---
layout: post
title: 気が抜けたのか
categories: 告知 サーバ
---

弊ブログのSSL証明書が Google Chrome の最新版において適切な要件を満たしておらず、ERR_CERT_COMMON_NAME_INVALID エラーを発生させていたので修正しました。

## 詳細

弊ブログのドメインは"blog.s6jr.com"ですが、SANのDNS名が"s6jr.com"になっていた(何でこんなミスしたんだろう……？)ために上述のエラーが発生。  
エラーを確認したのはWindowsとandroidそれぞれのChrome(78.0.3904.70, 77.0.3865.116)。  
証明書を正しく発行し直して対処しました。

## 随分気の抜けたミスだな……

と思うばかり。  
HPとブログを今年サーバ移転したんですが(厳密に説明しようとするとめんどくさいのでボカす)、寝惚けてる時にでもやったんだっけ……良くないな……