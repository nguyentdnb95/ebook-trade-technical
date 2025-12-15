# Chương 2: Đồ Thị 

Biểu đồ là công cụ làm việc của nhà phân tích kỹ thuật. Chúng đã được phát
triển dưới nhiều dạng và phong cách khác nhau để biểu diễn đồ họa hầu như
mọi thứ diễn ra trên thị trường, hoặc để vẽ ra một "chỉ số" được lấy từ đó.
Chúng có thể là biểu đồ tháng, trên đó toàn bộ dữ liệu giao dịch của một
tháng được rút gọn thành một điểm duy nhất, hoặc là biểu đồ tuần, ngày,
giờ, giao dịch, "điểm và hình thức", biểu đồ nến, v.v. Chúng có thể được
xây dựng trên thang đo số học, logarit, hoặc căn bậc hai, hoặc được biểu diễn
dưới dạng "dao động". Chúng có thể miêu tả các đường trung bình động, tỷ lệ
khối lượng giao dịch so với biến động giá, giá trung bình của các cổ phiếu
"hoạt động nhất", giao dịch lô lẻ, tỷ lệ bán khống, và vô số các mối quan
hệ, tỷ lệ và chỉ số khác — tất cả đều là kỹ thuật trong ý nghĩa rằng chúng
được lấy từ, trực tiếp hay gián tiếp, những gì thực sự đã được giao dịch trên
các sàn chứng khoán.
Với hầu hết các loại biểu đồ này, may mắn thay, chúng ta không cần phải
quan tâm đến chúng nhiều; chúng chỉ có ý nghĩa với các nhà phân tích kinh
tế toàn thời gian. Nhiều trong số chúng đã xuất phát từ một nỗ lực hoàn toàn
vô ích (ít nhất là cho đến nay) nhằm phát hiện ra một chỉ số "cơ học" hoặc
sự kết hợp của các chỉ số có thể luôn luôn, tự động, mà không bao giờ thất
bại hay sai lầm, cảnh báo về sự thay đổi xu hướng; những phương pháp như
vậy, theo kinh nghiệm của chúng tôi, thường gây bối rối và đôi khi thậm chí
gây hiểu lầm vào những thời điểm quan trọng nhất. Tuy nhiên, cuốn sách này
được thiết kế cho người bình thường, cho những người kinh doanh hoặc chuyên
gia không thể dành toàn bộ thời gian cho các hoạt động đầu tư hay giao dịch,
nhưng những hoạt động này, dù sao, lại đủ quan trọng hoặc hấp dẫn để khiến
họ dành ít nhất một vài phút mỗi ngày để nghiên cứu và quản lý chúng.
_(EN9: Nhìn lại, việc đánh giá thấp tầm quan trọng của công việc này. Vào thế
kỷ 21, các chuyên gia hàng đầu đều nhận thức rõ tầm quan trọng của phân tích
xu hướng và sử dụng công trình này như một cuốn sách giáo khoa.)_ Các lý thuyết
và phương pháp được trình bày ở đây chỉ yêu cầu dạng biểu đồ cổ phiếu đơn
giản nhất — một bản ghi phạm vi giá (giá cao và thấp), giá đóng cửa, và
khối lượng cổ phiếu giao dịch mỗi ngày. Những đồ thị hàng ngày này sẽ được
bổ sung, cho các mục đích nhất định sẽ được thảo luận sau, bằng các biểu đồ
tuần hoặc tháng, mà đối với hầu hết các cổ phiếu, có thể mua sẵn và dễ dàng
tạo ra bằng hầu hết các phần mềm đầu tư có sẵn trên thị trường.

Hầu hết các minh họa trong các trang tiếp theo đều là ví dụ về các biểu đồ
hàng ngày như vậy. Chúng dễ dàng vẽ và duy trì bằng tay, chỉ cần một ít giấy
biểu đồ hoặc giấy cắt ngang (hầu như loại nào cũng có thể sử dụng), một tờ
báo hàng ngày cung cấp báo cáo đầy đủ và chính xác về giao dịch chứng khoán,
một cây bút chì sắc và vài phút thời gian. _EN: Ngoài ra, có rất nhiều dịch
vụ dữ liệu có sẵn để sử dụng với các phần mềm máy tính, chưa kể các trang web
Internet (được đề cập trong Tài nguyên). Việc sử dụng công nghệ này loại bỏ
hoàn toàn gánh nặng của việc vẽ biểu đồ thủ công. Nếu có một nhược điểm của
công nghệ này, có lẽ đó là mất đi "cảm giác" mà nhà đầu tư có được thông qua
việc vẽ biểu đồ thủ công._

Thông thường, khi chuẩn bị các biểu đồ chứng khoán hàng ngày thông thường,
người ta để trục ngang biểu thị thời gian, với các đường chéo dọc (hoặc
như một số người ưa thích, các khoảng cách giữa chúng) từ trái sang phải
tương ứng với các ngày liên tiếp. Thang đo dọc được dùng để ghi giá, với
mỗi đường chéo ngang tương ứng với một mức giá cụ thể. Không gian thường
được dành ở dưới cùng của tờ giấy để vẽ khối lượng, tức là số lượng cổ phiếu
thay đổi chủ sở hữu mỗi ngày. Các tờ báo công bố báo cáo chứng khoán đầy đủ
cung cấp doanh thu hoặc khối lượng giao dịch của ngày (không bao gồm các giao
dịch lô lẻ có thể bị bỏ qua trong mục đích hiện tại của chúng ta), mức giá
cao nhất và thấp nhất mà mỗi cổ phiếu đã bán trong ngày, giá đóng cửa (là
giá tại thời điểm giao dịch cuối cùng trong ngày), và thường là giá mở cửa
hoặc giá giao dịch đầu tiên. Trên biểu đồ của chúng ta, phạm vi giá hàng ngày
được vẽ bằng cách vẽ một đường dọc nối các điểm đại diện cho mức cao và mức
thấp. Sau đó, một dấu ngang ngắn sẽ được thêm vào, có thể cắt ngang qua đường
dọc hoặc kéo dài ra phía bên phải từ nó, ở mức giá đóng cửa. Đôi khi, tất cả
các giao dịch trong một cổ phiếu trong ngày diễn ra tại một mức giá duy nhất;
giá cao, giá thấp và giá đóng cửa do đó sẽ nằm trên cùng một mức và dấu duy
nhất trên biểu đồ của chúng ta sẽ là dấu ngang đại diện cho giá đóng cửa.

Khối lượng được thể hiện bằng cách vẽ một đường dọc từ đường cơ sở của biểu đồ.
Giá mở cửa không cần phải ghi lại.* Kinh nghiệm đã chỉ ra rằng nó hiếm khi,
nếu có, có bất kỳ ý nghĩa nào trong việc ước tính các diễn biến tương lai,
điều mà thông thường chúng ta nên quan tâm. Tuy nhiên, giá đóng cửa là rất quan
trọng. Thực tế, đây là mức giá duy nhất mà nhiều người đọc báo tài chính chỉ
chú ý đến. Nó đại diện cho sự đánh giá cuối cùng của cổ phiếu được thực hiện
bởi thị trường trong suốt ngày hôm đó. Dĩ nhiên, nó có thể được ghi nhận trong
giờ giao dịch đầu tiên, nếu không có giao dịch nào khác được thực hiện sau
đó, nhưng nó vẫn là con số mà phần lớn các nhà giao dịch tiềm năng dựa vào
để lập kế hoạch cho ngày hôm sau. Do đó, giá đóng cửa có ý nghĩa kỹ thuật, và
nó sẽ xuất hiện trong các bối cảnh khác nhau trong các chương sau.

##### Các Loại Thang Đo Khác Nhau

Nhiều gợi ý cụ thể về chi tiết vẽ biểu đồ sẽ được thảo luận ở phần hai của
cuốn sách này, nhưng có một đặc điểm biểu đồ có thể được xem xét ở đây. Cho
đến những năm gần đây, hầu hết các biểu đồ giá cổ phiếu đều được vẽ trên loại
giấy đồ thị thông thường với thang đo số học. Tuy nhiên, ngày càng có nhiều
nhà phân tích biểu đồ sử dụng loại giấy được gọi là giấy bán logarit, hoặc đôi
khi gọi là giấy tỷ lệ hoặc giấy phần trăm. Kinh nghiệm của chính chúng tôi cho
thấy rằng thang đo bán logarit có những ưu điểm rõ rệt trong công việc này;
hầu hết các biểu đồ được tái bản trong cuốn sách này đều sử dụng nó. Hai loại
thang đo này có thể dễ dàng phân biệt qua việc trên giấy số học, các khoảng cách
bằng nhau trên thang đo dọc (tức là giữa các đường ngang) đại diện cho số
tiền bằng nhau theo đô la, trong khi trên giấy bán logarit, chúng đại diện cho
các biến động phần trăm bằng nhau. Do đó, trên giấy số học, khoảng cách giữa
10 và 20 trên thang đo dọc là hoàn toàn giống với khoảng cách từ 20 đến 30 và
từ 30 đến 40. Trên thang logarit, sự khác biệt từ 10 đến 20, đại diện cho một
sự gia tăng 100%, là giống như sự khác biệt từ 20 đến 40 hoặc từ 40 đến 80,
trong mỗi trường hợp đều đại diện cho một sự gia tăng 100% khác.

Mối quan hệ phần trăm, không cần phải nói, rất quan trọng trong giao dịch cổ phiếu.
Giấy bán logarit cho phép so sánh trực tiếp giữa cổ phiếu giá cao và giá thấp,
và làm cho việc lựa chọn cổ phiếu có tỷ