rs485_hdlc_ret
==============

Implementation of the Iuant interface layers in c (based on rs485)

This project is based on Iuant specification available at http://www.arib.or.jp/english/html/overview/doc/STD-T104v2_30/2_T104/ARIB-STD-T104/Rel10/25/A25460-a01.pdf

which was referring to these 3 documents to understand each of the 3 layers used in Iuant interfacing :

Layer 1 : http://www.arib.or.jp/english/html/overview/doc/STD-T104v2_10/2_T104/ARIB-STD-T104/Rel10/25/A25461-a30.pdf

Layer 2 : http://www.arib.or.jp/english/html/overview/doc/STD-T104v1_00/5_Appendix/Rel10/25/25462-a10.pdf

Layer 3 : http://www.arib.or.jp/english/html/overview/doc/STD-T104v2_30/5_Appendix/Rel11/25/25466-b30.pdf


In this implementation, I choosed to use the RS485 option for Layer 1 (Physical Layer).

Testing will be done mainly on BeagleBone Black.

More platforms may be added later on.
