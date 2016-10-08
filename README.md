# Homework 1 - *Name of App*

**Name of your app** Trang web cho phép người dùng chia sẻ và cập nhật trạng thái. Due Date: 24:00 11/10/2016

Danh sách sinh viên: **Your Name Here**

URL: **Insert your Heroku URL here**

## Chức năng

Danh sách chức năng **bắt buộc**:

* [ ] Người dùng được phép đăng nhập bằng tên tài khoản, mật khẩu.
* [ ] Người dùng có thể đăng trạng thái lên trang cá nhân.
* [ ] Ở trang home, người dùng có thể xem trạng thái của bạn bè và những người đang được người đó follow. Cần thể hiện đầy đủ thông tin của trạng thái như hình ảnh, avatar,...
* [ ] Người dùng có thể tìm kiếm người dùng khác
* [ ] Người dùng có thể follow người dùng khác
* [ ] Người dùng có thể thêm comment vào các bài đăng.
* [ ] Người dùng có thể đăng nhập bằng Twitter qua OAuth(Sử dụng Omniauth Twitter)
* [ ] Sử dụng Twitter API để cho phép tạo tweet lên Twitter của người dùng khi đăng trạng thái thành công (Sử dụng [Twitter Gem](https://github.com/sferik/twitter) và [đăng ký Application Token](https://apps.twitter.com))
* [ ] Cần thể hiện số ký tự còn lại khi gõ (Twitter cho phép gõ trạng thái tối đa 140 ký tự)
* [ ] Cần thực hiện AJAX và javascript để hạn chế nạp lại trang.
* [ ] Cho phép tải danh sách các tweet vào trang chủ của người dùng
* [ ] Cần quản lý API Key bằng biến môi trường (Sử dụng [dotenv gem](https://github.com/bkeepers/dotenv))

Danh sách chức năng **phụ**:

* [ ] Tự động load thêm các tweet mới khi kéo xuống cuối trang.
* [ ] Người dùng được phép khởi tạo mật khẩu. Khi nhấn vào nút khởi tạo mật khẩu thì hệ thống sẽ gửi mail cho người dùng link xác nhận, nhấn vào link sẽ đến trang nhập mật khẩu mới.
* [ ] Cho phép retweet, favorite các tweet ngay từ trang chủ
* [ ] Cho phép follow/unfollow người dùng từ twitter
* [ ] Cho phép tìm kiếm người dùng twitter
* [ ] Người dùng được phép thấy tweet sau khi đã thêm thành công mà không cần tải lại trang
* [ ] Retweet và favorite sẽ làm tăng số lượng người dùng retweet và favorite của mỗi tweet mà không cần tải lại trang
* [ ] Cần test các model validation với rspec
* [ ] Cần tạo các test với capybara và rspec để test chức năng của ứng dụng

Danh sách chức năng **thêm** đã làm nhưng chưa được liệt kê ở trên:


Quy trình sử dụng [GIT Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/)
* [ ] Git với Centralize Workflow (chỉ có duy nhất nhánh master)
* [ ] Git theo Feature Branch Workflow (mỗi chức năng sẽ được làm trên 1 nhánh riêng)
* [ ] Git theo Gitflow Workflow (Có các nhánh develop, master, test,...)
* [ ] Có sử dụng tag, pull requests

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![Video Walkthrough](relative-path-to-your-gif-file-on-github)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
