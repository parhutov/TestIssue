# TestIssue

�������� (����������) ���������, ����������� �� ���� ��� ����� � ����� ����������. � ����������� �� ���������� ��������� ������ �������� � ��� �������:
1. test -f Test.tst -m words -v mother � �������� ���������� ���� �mother� � ����� �Test.tst�
2. test -f Test.tst -m checksum � �������� 32-������ ��������, ������������ �� ��������� checksum = word1 + word2 + ... + wordN (word1..wordN � 32-������� �����, �������������� ���������� �����)
3. test -h � �������� ���������� � ��������� � �������� ����������.
��� ��������� ��������� ������� �� ������� ������� ������ ������������� production-���� �� �++ (� �� ������� �, �������� �� ��������� ������������ �++ ��� ������ ������),  � ���������:
- ���������� ������� ����� �����������
- �������� ������������ ������
- ������ �� ������������������
- ������ �� �������������
- ���������� ��������� ��� ���, ��� ��� �������
- ������������� modern C++ best practices

# build:

`cmake ./out/build && cmake --build ./out/build`