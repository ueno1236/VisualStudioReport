# Debug of VisualStudio

## Breakpoint

���삪�������ӏ����u���[�N�|�C���g�ŋ���őO��̕ϐ��̕ω�������

BreakPoint�̎g�p���@  
�\�[�X �R�[�h�Ƀu���[�N�|�C���g��ݒ�
�f�o�b�O->�u���[�N�|�C���g�̐ݒ�/�����v���瑀��o�邪�uF9�v�L�[�ł������������

[![Image from Gyazo](https://i.gyazo.com/f44bbd93f74e890e54d94f180e0d6a35.png)](https://gyazo.com/f44bbd93f74e890e54d94f180e0d6a35)

�f�o�b�O����ƁA���̍s�̃R�[�h�����s�����O�ɁA�u���[�N�|�C���g�Łu���s���ꎞ��~���܂��B �u���[�N�|�C���g �V���{���ł́A���F�̖��{�^���������Ă��܂��B

[![Image from Gyazo](https://i.gyazo.com/0f1cb1bcc9141ad5cc2ee9d865806cb4.png)](https://gyazo.com/0f1cb1bcc9141ad5cc2ee9d865806cb4)

�u���[�N�|�C���g�Ńf�o�b�K�[����~������A�ϐ��̒l�Ȃǂ̃A�v���̌��݂̏�Ԃ��m�F�ł��܂��B

>�u���[�N�|�C���g�́A���s�\�t�@�C���̔C�ӂ̃R�[�h�s�ɐݒ�ł��܂��B  
�Ȃǂ̎��� c# �R�[�h�A����\��������܂��Ƀu���[�N�|�C���g��ݒ�ϐ��̐錾�Afo���[�v�A�܂��͔C�ӂ̃R�[�h���ŁAfor���[�v���܂��B  
���O��Ԃ܂��̓N���X�錾�A�܂��̓��\�b�h �V�O�l�`���ł́A�u���[�N�|�C���g��ݒ�ł��܂���B

---

## Step in

step in�́@1�s�i�݊֐��̒��ɓ���ϐ��̒l���m�F���邱�Ƃ��ł���B  
�m�f�o�b�O�n���j���[�́m�X�e�b�v�C���n(F11)

[![Image from Gyazo](https://i.gyazo.com/7cc3837996a21016b36da9de1d9f1148.png)](https://gyazo.com/7cc3837996a21016b36da9de1d9f1148)

## Step out

�����Ԉ���āA��������Ȃ��ėǂ��Ǝv���֐�(���\�b�h��v���p�e�B)�̒��ɓ����Ă��܂����ꍇ�ɂ́A�m�f�o�b�O�n���j���[�́m�X�e�b�v�A�E�g�n(Shift�{F11)�𗘗p�ł���B

[![Image from Gyazo](https://i.gyazo.com/7815e94dc1d7ef64936c8d660a5b8d31.gif)](https://gyazo.com/7815e94dc1d7ef64936c8d660a5b8d31)

## Step over

�֐��܂��̓��\�b�h�Ăяo���̃R�[�h�s�ɂ���Ƃ��AF11 �̑���� F10 ���������Ƃ��ł��܂�  
�m�f�o�b�O�n���j���[�́m�X�e�b�v�I�[�o�[�n(F10)  
F10 �L�[�������ƁA�A�v�� �R�[�h���̊֐��܂��̓��\�b�h�ɃX�e�b�v �C�����邱�ƂȂ��A�f�o�b�K�[���i�߂��� (�R�[�h�͂܂����s����Ă�)�B  

[![Image from Gyazo](https://i.gyazo.com/7811157a8b2f677adfc4f63bbb52cd0f.gif)](https://gyazo.com/7811157a8b2f677adfc4f63bbb52cd0f)

F10 �L�[���������ƂŁA�֐S�̂Ȃ��R�[�h���X�L�b�v�ł��܂��B ���̕��@�ɂ��A�֐S�̍����R�[�h�܂ł��΂₭���B�ł���B

>Visual Studio �̂悤�ȃf�o�b�O �c�[���ŃR�[�h�� 1 �X�e�b�v�����s���A�v���O���~���O���Ԉ���Ă���ӏ��𐳊m�ɔ������邱�Ƃ��ł��邽�ߌ��ʓI�B  
���ɁA�s���K�v������R�[�h�C���𗝉����܂����A�����̏ꍇ�A�f�o�b�O �c�[���ł́A�v���O�����̎��s�𑱂��Ȃ���A�ꎞ�I�ɕύX���Č��邱�Ƃ��ł���B

---

## �����ϐ��E���[�J���ϐ��E�B���h�E  

�ϐ��̌��݂̒l���m�F�ł���E�B���h�E

���s���f���ɁA�f�o�b�O���j���[�̃E�B���h�E���j���[�̒��̒��i������Ɂu�E�H�b�`�v�u�����ϐ��v�u���[�J���v�Ƃ������j���[������ł���B  
������I������ƁA�ϐ��̒��g���m�F���邽�߂̃E�B���h�E���J��

���[�J���E�B���h�E  
�S�Ă̕ϐ����\������Ă��܂��B�܂��g�p����Ă��Ȃ��ϐ����\������܂��B  
[![Image from Gyazo](https://i.gyazo.com/6da32fee013e037df0cf4060d273fb6e.png)](https://gyazo.com/6da32fee013e037df0cf4060d273fb6e)

���Ɏ����ϐ��E�B���h�E  
�u���[�N�|�C���g��ݒ肵���s�̕ϐ��ƁA���̑O�̍s�Ŏg�p����Ă���ϐ����\������Ă��܂��B  
[![Image from Gyazo](https://i.gyazo.com/86ae6df5728a56a2323aad548801b69c.png)](https://gyazo.com/86ae6df5728a56a2323aad548801b69c)

---

## �E�H�b�`��  

�v���O�������f�o�b�O���s����ƁA�u���[�N�|�C���g�܂Ŏ��s���i�񂾎��_�ŁA���s�����f����AIDE(�����J����)�����Ɂm���[�J���n�E�B���h�E�A�m�E�H�b�` 1�n�E�B���h�E�Ȃǂ��\�������B  
[![Image from Gyazo](https://i.gyazo.com/f5d2a8d2d77a49ddd1fd53ed20751992.png)](https://gyazo.com/f5d2a8d2d77a49ddd1fd53ed20751992)

�m�E�H�b�`�n�E�B���h�E�ɃE�H�b�`����ǉ�����ȒP�ȕ��@�́A�f�o�b�O���s�����f������ԂŁA�E�H�b�`�������Ώۂ��E�N���b�N���āA�R���e�L�X�g���j���[����m�E�H�b�`�̒ǉ��n��I������
[![Image from Gyazo](https://i.gyazo.com/9513b24c8dab59d809ac3dd3d294afe4.png)](https://gyazo.com/9513b24c8dab59d809ac3dd3d294afe4)

>�m�E�H�b�`�n�E�B���h�E���g���ƁA�v���O�����̃f�o�b�O���s���ɂ��܂��܂ȏ����A�v���O���}�[���]�ތ`�ŕ\���ł���悤�ɂȂ�B���̒ǉ��͂ƂĂ��ȒP�ɍs���A���̕ҏW�������ɂł���B�܂��A��K�͂ȃv���O�����ł́A�ő�4�܂ł́m�E�H�b�`�n�E�B���h�E�Ɋ֘A�̂����񂾂����܂Ƃ߂ĕ\�����邱�Ƃ��\���B�g�����Ȃ��΁A�f�o�b�O���������I�ɍs����悤�ɂȂ邾�낤�B

---

## �f�[�^�u���C�N�|�C���g

����̕ϐ����l�ω������u�ԂɁA�Y������\�[�X�R�[�h�̕����Ńv���O�������~�����邱�Ƃ��ł���

1. �C�ӂ̏ꏊ�Ńu���[�N�|�C���g��u���ăv���O�����𒆒f������

1. ���j���[�o�[��[�f�o�b�O] -> [�u���[�N�|�C���g�̍쐬] -> [�f�[�^�u���C�N�|�C���g]���N���b�N����

1. �f�[�^�u���[�N�|�C���g��ݒ肷��A�h���X����͂���

[![Image from Gyazo](https://i.gyazo.com/00e20c5a02376d7e50e4563c7396804e.png)](https://gyazo.com/00e20c5a02376d7e50e4563c7396804e)

�f�[�^�u���[�N�Ɉ���������Ɖ��L�̂悤�ȃ_�C�A���O���\�������B

[![Image from Gyazo](https://i.gyazo.com/b61330da743729f0a88f2789f2e62d01.png)](https://gyazo.com/b61330da743729f0a88f2789f2e62d01)

>�v���O���~���O�����Ă���ƁA�z��O�̕s����������邱�Ƃ͂悭����B  
�ς��͂��̂Ȃ��ϐ��̒l���ς���Ă�����A�ˑR�v���O�����������I��������Ɨl�X�B  
����Ȏ��ɗ\�z�����s����������j��B  
�������j��͔j�󒼌�ɗ������ɁA�j�󂵂����������Q�Ƃ����Ƃ��ɏ��߂ĕs��������鎖�������̂ŁA�s��̌����𒲍�����̂�����B  
���̏ꍇ�ɗL���ɂȂ�̂��f�[�^�u���C�N�|�C���g�ł���B

---

## �������E�B���h�E

�������E�B���h�E�́A�f�o�b�O �Z�b�V�������ɂ̂ݎg�p�ł���

�������E�B���h�E���J���ɂ�

1. �c�[�� > �I�v�V����(�܂��̓f�o�b�O > �I�v�V����) >�f�o�b�O > �S��

1. �ΐF�̖���I�����ăf�o�b�O���J�n�L�[��������F5�A�܂��͑I���f�o�b�O > �f�o�b�O�̊J�n

1. �f�o�b�O > Windows > ������  
(�ꕔ�̃G�f�B�V������Visual Studio1 �����񋟃������E�B���h�E)

[![Image from Gyazo](https://i.gyazo.com/90df7e5b6432ae8b33f8980d6fa9c0c7.png)](https://gyazo.com/90df7e5b6432ae8b33f8980d6fa9c0c7)

* ���������Ń|�C���^�[��ǐՂ���ɂ�

  1. �A�h���X�Ƃ��ĕ]�������|�C���^�[�������  
[![Image from Gyazo](https://i.gyazo.com/7aa43a2ebfd6114c6ec4f6654b92cf03.png)](https://gyazo.com/7aa43a2ebfd6114c6ec4f6654b92cf03)

  1. �_�u���N���b�N�Ń|�C���^�ϐ���I�����āA�������E�B���h�E�Ƀh���b�O&�h���b�v����
[![Image from Gyazo](https://i.gyazo.com/b05379e3a75acace89d3a8bd819e0eda.gif)](https://gyazo.com/b05379e3a75acace89d3a8bd819e0eda)

>�������̓��e���Ď�����B  
�v���O�����̎��s���ɕς�邷�ׂĂ̒l��16�i�ŕ\�������

---

## �R�[���X�^�b�N(�Ăяo������)

���̋@�\�́A�u���[�N�|�C���g�Ƒg�ݍ��킹�Ďg�p����B  
�u���[�N�|�C���g�ɂ���Ď��s���ꎞ��~�����A���̎��_�܂łɂǂ̂悤�Ȍo�H�����ǂ��āA���݂̊֐��ɓ��B�����̂����m�F�ł���B

�R�[���X�^�b�N���J���ɂ�  
���j���[�o�[����y�f�o�b�O�z���y�E�B���h�E�z���y�Ăяo�������z��I������  
�V���[�g�J�b�g�L�[�� Alt + 7
[![Image from Gyazo](https://i.gyazo.com/cd57ab56b0e47bacebb80031c8c6014f.png)](https://gyazo.com/cd57ab56b0e47bacebb80031c8c6014f)

���[�̉��F����󂪁A���݂̎��s�ʒu�������Ă���B�Ȃ̂ŉ��̍s�ɍs���قǁA�����i�K�ŌĂяo���ꂽ�֐��ƂȂ�B

�����ŏ������v���O�����łȂ������́A�u�O���R�[�h�v�ƕ\�������B

> �y�Ăяo�������z�E�B���h�E�ŁA�s�̏�Ń_�u���N���b�N����ƁA�f�o�b�O�̃R���e�L�X�g�i�����j��؂�ւ�����B  
�܂�A���̊֐������s����悤�Ƃ��Ă������_�ł̏󋵂ɁA�e��f�o�b�O�\����؂�ւ�����  
**���̂Ƃ��A�y�Ăяo�������z�E�B���h�E�̕��́A���[�ɗΐF�̖�󂪕\�������B**  
�f�o�b�O�̃R���e�L�X�g��؂�ւ��邱�Ƃɂ���āA�ʂ̊֐��ł͂ǂ�ȏ󋵂ł��������𒲂ׂ邱�Ƃ��ł���

---

## �C�~�f�B�G�C�g�E�B���h�E

�C�~�f�B�G�C�g�E�B���h�E���J���ɂ�  
[�f�o�b�O] ���j���[�� [�E�B���h�E] > [�C�~�f�B�G�C�g]

���̋@�\�́A�u���[�N�|�C���g�Ƒg�ݍ��킹�Ďg�p����  
break point �Ŏ~�܂��Ă���Ƃ��ɃC�~�f�B�G�C�g�E�B���h�E�ɃR�[�h��łƕ]�����Č��ʂ��m�F�ł���

[![Image from Gyazo](https://i.gyazo.com/eaee8b2d4470d3e492185cab51490027.png)](https://gyazo.com/eaee8b2d4470d3e492185cab51490027)

**�l���󂯎���ĕ\�����邾���łȂ� �l�̕ύX���ł��܂�
�������]������Α�����ł��܂�**

[![Image from Gyazo](https://i.gyazo.com/9e042a1684b74ef5f00534c5c748bd9f.png)](https://gyazo.com/9e042a1684b74ef5f00534c5c748bd9f)

>�C�~�f�B�G�C�g�Ƃ������t�́u�����́v�Ƃ����Ӗ��������Ă���B  
�C�~�f�B�G�C�g�E�B���h�E�́A�m�肽�����ƁE�m�F���������Ƃ𑦎��ɒm�邱�Ƃ��ł���E�B���h�E�B

---

## Debug tool ���g�p����ƁA��O�����������R�[�h���̏ꏊ�𐳊m�ɓ���ł��A�l������C�����@�𒲍�����̂ɖ𗧂��܂�

---
