# WORKING NOTES

## 29/03/2024 - 28/04/2024

- [ ] Thêm UI cho get all friends fb

- [ ] <https://github.com/lelinhtinh/Userscript>

- [x] tiktok download api lỗi => Dùng snaptik api

- [ ] cào data tiktok/douyin <https://github.com/Evil0ctal/Douyin_TikTok_Download_API>

- [ ] fb_invisible_message có vẻ không hoạt động

- [x] fb_whoIsTyping có vẻ không hoạt động => chỉ hoạt động nếu ko mã hoá

- [ ] zing mp3 - có api ngon mà chưa dùng hết chức năng

- [x] tất cả các script inject code vào website cần update để tuân thủ TrustedScript

- [ ] Tổng hợp các chức năng tải hàng loạt fb vào 1 trang web mới

- [ ] Test thử [rapid api](https://rapidapi.com/)

- [ ] Youtube local download => lấy data từ ytplayer.config.args.raw_player_response => Làm UI

- [ ] html2img khá ngon, nhưng chưa biết xài vô cái gì

- [x] Optimize import jszip => có lẽ không cần

- [x] làm cho xong soundcloud_downloadMusic hoặc xóa => Xong rồi, Ngon

- [x] Move transfer.sh sang popup => Xoá luôn

- [x] text to qrcode không còn hoạt động => xoá luôn, ít xài

- [ ] bookmark exporter/manager

- [x] Google docs/sheet downloader => Done

- [x] Tailieu.vn => PDFjs dễ crack

- [x] Wheel of name - input list of values

- [x] duck race - input list of values

- [ ] fb_getAllUidOfGroupMembers đang lỗi

- [x] text to qrcode <https://hoothin.com/qrcode/>

- [x] extension ngon cho youtube [Improved youtube](https://chromewebstore.google.com/detail/improve-youtube-%F0%9F%8E%A7-for-yo/bnomihfieiccainjcjblhegjgglakjdd?authuser=1)

- [ ] Fix hack wheel of names

- [x] Thêm visualize music vào bất kỳ trang web nào => repo riêng

- [x] get bigest image: <https://greasyfork.org/scripts/2312> <https://github.com/hoothin/UserScripts/blob/master/Picviewer%20CE%2B/pvcep_rules.js> => check rule r array and s array

- [x] hoc regex di <https://github.com/regexhq> <https://www.regexbuddy.com/>

- [x] đọc extension samples <https://github.dev/GoogleChrome/chrome-extensions-samples>
  - [x] Run auto script from background service worker chrome.webNavigation.onDOMContentLoaded
  - [x] Sử dụng chrome.downloads
  - [x] Tìm hiểu chrome.topSites => không có nhiều ý tưởng lắm
  - [ ] permissions userScripts
  - [x] chrome.power => keep PC awake => we dont need this
  - [ ] chrome.windows => merge windows
  - [ ] offscreen clipboard write => Copy selected text on any web?
  - [ ] tabCapture => capture google meet?
  - [ ] webSocket => do something great?

- [x] Thêm change logs cho từng scripts

- [ ] Xem google extension howto [Link](https://developer.chrome.com/docs/extensions/how-to)
  - [x] record audio and video from another tab [link](https://developer.chrome.com/docs/extensions/how-to/web-platform/screen-capture) => **TIỀM NĂNG làm web visualize music**
  - [x] chụp ảnh website bằng chrome.tabs.captureVisibleTab => bỏ, không có tiềm năng
  - [x] chrome.tabCapture [link](https://developer.chrome.com/docs/extensions/reference/api/tabCapture) => access MediaStream of current tab => phải là 1 page trong extension mới truy cập được => không tiềm năng
