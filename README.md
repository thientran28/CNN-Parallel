# CNN-Parallel
Parallelize Convolutional Neuron Network Layer For Image Classification

Our team's member:
- 19127281 - Trần Minh Thiện  
- 19127154 - Nguyễn Thế Hưng  
- 19127330 - Lê Tâm Anh  


**Vấn đề đặt ra cho bài toán song song hóa mạng CNN**
- A Convolutional Neural Network là một dạng deep neural network, thường được áp dụng cho việc phân loại hình ảnh. CNN sẽ bao gồm 3 layer chính đó là convolutional layer, max-pooling layer và fully connected layer và trong CNN ta phải thực hiện nhiều các phép tính giữa các ma trận với nhau nên có thể nói đây là điểm đặc biệt của thuật toán để ta khai thác và thực hiện song song hóa giảm tốc độ chạy cho network. 

- Ở trong thuật toán CNN, ta có thể thực hiện song song hóa các hàm forward và backward trong các lớp cùng với việc cải thiện tốc độ của một số hàm tính toán hai ma trận trong lớp CNN để giảm dung lượng bộ nhớ và đạt được tốc độ cao lên với chi phí giảm độ chính xác thấp nhất có thể

- Tập dataset được sử dụng trong bài ở đây sẽ là tập MNIST dataset, một tập dataset chửa khoảng 60,000 các chữ số viết tay thường được sử dụng trong việc training các hệ thống xử lý hình ảnh. 
Trong đồ án này, ta sẽ sử dụng 10000 ảnh để train và kiểm thử cho việc cải thiện thời gian chạy cho thuật toán song song.
