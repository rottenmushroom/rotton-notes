---
layout: post
title:  "使用者訪談初體驗"
date:   2017-02-06 16:40:00 +0800
categories: course
---

密西根大學資訊學院的[人機互動](https://www.si.umich.edu/academics/msi/human-computer-interaction-hci)（Human Computer Interaction）名聲非常響亮，去年他們總算在 edx 開了網路學程，命名為「[User Experience (UX) Research and Design](https://www.edx.org/micromasters/michiganx-user-experience-ux-research-and-design)」，目前共有 8+1 堂課：

* Introduction to User Experience
* Principles of Designing for Humans
* Evaluating Designs with Users
* UX Design: From Concept to Wireframe
* UX Design: From Wireframe to Prototype
* Understanding User Needs
* UX Research Surveys
* UX Research at Scale: Analytics and Online Experiments

最後一個是 capstone，也就是學生必須做出完整的 project。

所有課程都是 self-paced，當然還是得趕在截止期限 2017 年 10 月前完成，不然課程應該就歸檔了，我猜應該還是可以看影片教材，但無法上傳作業，進行 peer review。如果沒有練習跟實作，上這些課坦白說一點意義也沒有。而且交完作業若有得到 feedback，往往是最大的收穫。

最近開始認真選修第一堂使用者體驗入門，教師 Mark Newman 很仔細地講解 User Experience 的基本概念，理論筆記我不多談。這篇主要是紀錄第一次作業：邀請兩位朋友使用 Doodle 服務完成指定任務，並且進行觀察與訪談。

Doodle 是一個「揪團喬時間（中文介紹可以[看此](https://free.com.tw/doodle/)）」。本文主要是以中文紀錄我的心得。

#### 關於主辦活動確認時間

大學時很常在 PTT 看到或使用這種回覆出席與否的格式（隨便搜尋的，如有不妥請通知我）：

![](http://i.imgur.com/bOAzQGc.png)

現在比較流行的方法應該是直接在線上聊天群組裡丟個訊息「哪時有空？」然後有幾個人永遠沒有回音。受訪者 A 就是這種方式，但他不厭其煩還是會私下丟那些遲遲沒有回覆的人請他們確定。受訪者 B 則是寧可直接一個一個問，因為他知道在群組裡問 87% 不會有下文。

雖然有用，但還是很缺乏效率。所以有了 Doodle 這種讓所有參與者自己填寫時間，主揪不用再自虐的服務。

#### 初探 Doodle

我的兩名受訪者都是<del>交際花</del>，一個月主揪 5687 次都不奇怪，請他們測試 Doodle 應該是很合適的對象。先說結論好了，他們都覺得 Doodle 的<b>概念</b>很好，想解決的問題有打到主揪們的心坎裡，但真正使用的過程卻是障礙重重，這服務沒走紅真的是有原因的。

包括我在內，我們三個共同遇到的大問題有兩個：

**[1] 設定時間**

![](http://i.imgur.com/zn8b3XM.png)

課堂要求的其中一項 task 是：

> 活動長度一小時，時間可介於 5pm - 8pm。

選擇日期之後，進入填寫時間的頁面。看到這樣的畫面我們都愣住了（受訪當然是不同時間、不同地點）。時間屬於封閉性問題，但格式又不固定，整片空白的欄位卻沒任何提示，使用者該怎麼正確的填寫時間呢？17、17:00、5:00、05:00 都可以代表五點，何況還有 AM/PM 之分，以及一個小時的區間該怎麼呈現？

雖然只要使用者試著輸入 17:00，系統會自動更正成 5:00PM，不過一來使用者不知道，二來一定會有一堆系統也無法判斷的例外。這個設計讓人非常困惑，我用 keynote 畫了一個簡單的改善方案：

![](http://i.imgur.com/UK4ItU4.png)

我把時間設定從空白欄位改成下拉選單，並有預設的時間，使用者不必自己輸入，直接按小箭頭更改就可以了。這應該比較符合我們平常用 Google Calendar 設定時間的習慣（吧）。

另外，我把本來在下方的「Add time slots（增加時間）」、「Copy and paste first row（複製第一欄的時間至所有欄位）」移到上方，並且增加設定長度的選項，如此一來使用者只要設定開始時間，系統就會自動計算結束時間。

**[2] 進階設定**

另外一個要求是：

> 如果 Doodle 有這項功能的話，請讓使用者可以在 Yes/No 之外，也能選擇「這個時間最好不要，但若大家只有那天有空，我也可以出席」（這是我粗略翻譯的意思）。

![](http://i.imgur.com/Xro5swq.png)

![](http://i.imgur.com/R8YD9e8.png)

Doodle 的確有這個功能，但卻藏在 Settings 裡面，這也是讓人不解的設計。使用者搞定時間後，進入下一個步驟，這個頁面告訴我們，「如果基本功能已經夠了，你可以跳過這個步驟，不然你也可以點選下面的選項進行進階設定」，底下是 Back 跟 Next 的按鈕，接著才有一個「Setting」的標題，得再點選才會出現選項。

兩位受訪者在這步踟躕很久，A 是一直沒有意識到可以按下 Settings，上頁下頁來來回回，我稍微暗示後才知道原來那裡還有玄機。B 儘管一進到這一頁、快速閱讀說明後就按了 Settings，但兩位看了選項也都十分猶豫。兩位都是英語系國家念過書的人，語言應該不是問題，不過「Yes-No-Ifneedbe poll」讓他們萬分疑惑，雖然最後兩位都勾選了也順利完成任務。我本來覺得也許是我們不熟慣用語的原因，不過 peer review 看到不少同學的受測者也在這個選項的打轉，這裡的「Ifneedbe」應該改成更清晰、更直覺的用詞。

總結而言，把「基本」跟「進階」分開，就 Doodle 來說，實在非常多餘。使用者並不知道什麼叫基本、什麼叫進階，既然都多了一個新的頁面，為何不直接把可以選擇的項目直接列出來？不然真的只需要 Doodle 所定義的「基本功能」的使用者開新頁面是開心酸的嗎？我認為「Basic Poll」可以移除，使用者進入這頁時，就直接讓他們看到 Settings 所有選項，其實總共也才只有四個，說明也夠精簡，不致於讓人眼花撩亂。