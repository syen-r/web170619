# ����H1
## ����H2

* �б�1
* �б�2
* �б�5
* �б�5
* �б�25
* �б�1


# �ҵĵ�һ�ι���github

Ϊ�˼���������뿴һ��ע�ͣ�����git��


�汾��������
    git��svn������
	svn������ʽ
	git���ֲ�ʽ

ʶ���û��������룺
<code>
	$ git config --global user.name "Your Name"
	$ git config --global user.email "email@example.com"
</code>

ͨ�� git init ����ѵ�ǰ��Ŀ¼���һ���ֿ�

ע�⣺dir�޸�Ϊls  ʹ��ls -ah���Բ鿴�����ļ�

�汾������ļ���
   git add filename
�汾���ύ�ļ�
   git commit -m ����ע��
�鿴�汾��״̬��
   git status
�鿴�ļ����޸ģ� ��Ҫ�ļ�û�б���Ӻ��ύ�ſ��Բ鿴
   git diff
�鿴��ʷ�汾
   git log 
   �������Ϣ��git log --pretty=oneline
���˻�ص�ĳ���汾
   git reset --hard HEAD^ (�汾����)

���������ݴ�����
    ����������ǰ���ڱ�д���������
    �ݴ�����ͨ��git add�ύ������

�����޸ģ�
    ��������ո��������⣺
        1.ÿ���޸���ǵ�add
        2.����ʲôʱ��ȫ��add���ύ

�����޸ģ�
     git checkout -- filename

git��github�Ĺ�ϵ��githubʹ��git��ΪΨһ�����йܷ���

������ϲ���֧��
    �鿴��֧��git branch
    ������֧��git branch <name>
    �л���֧��git checkout <name>
    ����+�л���֧��git checkout -b <name>
    �ϲ�ĳ��֧����ǰ��֧��git merge <name>
    ɾ����֧��git branch -d <name>

��ͻ���ֶ��޸��ļ�


����github��
    1.����github��git remote add origin git@github.com:Geekiwen/hello.git
    2.�����ذ汾�����͵��������ϣ�git push -u origin master