# Advanced-Gyro-Calculater for EV3-G

ev3のジャイロセンサーにはセンサー値が永続的に増減するバグがあります。
これらのバグはセンサーに接続されているケーブルを再接続することで解決しますが、競技中にそれらを行うことは不可能です。
プログラム上からハードウェアリセットを可能にするサードパーティー製ブロックはありますが、それらのブロックは競技中に実行するには時間がかかります。
そこで、センサー値の増減のバグが発生していながらもジャイロセンサーを使えるようにする計算ブロックを製作しました。
このブロックをインポートするにはev3bファイルをダウンロードしてください：[Latest release](https://github.com/tanaka8610/Advanced-Gyro-Block/releases)


The gyro sensor in ev3 has bugs that cause the sensor value to increase or decrease permanently.
These bugs can be resolved by reconnecting the cables connected to the sensors, but it is impossible to do those things during competition.
There are third-party blocks that allow hardware resets from within the program, but these blocks take time to execute during competition.
Therefore, we have created a calculation block that allows the gyro sensor to be used despite the sensor value increase/decrease bugs.
You can download ev3b file to import this block：[Latest release](https://github.com/tanaka8610/Advanced-Gyro-Block/releases)
