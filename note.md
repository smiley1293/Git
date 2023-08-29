# Terms

Repository (Repo): kho, thư mục dự án của chúng ta
Branch
Conflict
Local
Remote

# Commands:

- git init
- git status: cho thấy đc trạng thái
- git add: cho phéo chuẩn bị lưu lại thời điểm của file
- git add . : cho phép chuẩn bị lưu lại tất cả các file
- git reset: hoán tác việc chuẩn bị lưu file
- git commit -m 'nội dung comment': chính thức lưu
- git log: ghi lại lịch sử
- git log --oneline: thấy các commit gọn hơn
- git checkout id: trở lại cái cmmit mình muốn(id tự nhập)
- git checkout {branch name}: chuyển sang branch mình muốn
- git branch: check branch
- git checkout -b {branch name}: tạo branch mới
- git merge {branch name}: hợp nhất các nhánh vào nhánh hiện tại
- git branch -d {branch name}: xóa nhánh mà mình muốn
- :q : thoát các tiến trình hiện tại
  --------------Kết thúc cơ bản---------------------
  \*\*Nâng cao kết hợp với github
- git push: đẩy lên local repo trên remote repo
- git remote add {name} {repo link}: tạo alios có tên name, sau này khi cần push code chỉ cần gõ "git push name {branch name}" là sẽ push code lên
- git push -u origin {branch name}: tạo thêm 1 branch trong dự án remote có tên là origin
- git fetch origin: kéo các branch trên dự án remote có tên origin
  (git checkout -b staging origin/staging)
- git push origin {branch name}

- git pull <remote> <branch> : lấy code từ nhánh của dự án remote nào đó
- Fork (Git hub): lấy dự án hoặc mã nguồn mở về github của mình
  ***
