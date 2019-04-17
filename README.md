# NguyenNangSon_Deque
BÀI TẬP KIỂM THỬ

Họ và tên: Nguyễn Năng Sơn
MSV: 16022480
Lớp: K61-CA-CLC2
Hàm đã chọn:
https://github.com/TheAlgorithms/C-Plus-Plus/blob/master/Data%20Structure/Queue%20Using%20Array.cpp

void Deque()
{
if (front==rear)
{
cout<<"\nUnderflow";
}

else
{
	cout<<"\n"<<queue[front++]<<" deleted";
	for (int i = front; i < rear; i++)
	{
		queue[i-front]=queue[i];
	}
	rear=rear-front;
	front=0;
}
}

Bước 1 : Lập đồ thị

code2flow_gyZ9FW
