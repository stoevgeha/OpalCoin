sudo apt-get install libssl-dev libdb-dev libdb++-dev libqrencode-dev qt4-qmake libqtgui4 libqt4-dev libminiupnpc-dev libminiupnpc8 libboost-all-dev build-essential git

git clone https://github.com/opalcoin/opalcoin.git

cd opalcoin

qmake USE_UPNP=- USE_QRCODE=0 USE_IPV6=0

make

./opalcoin-qt
