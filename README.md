# Projeto Integrador 3 2020/1
Lawn mower robot

Pré desenvolvimento de um robô cortador de grama, onde nesta disciplina será realizado a parte de sensoriamento e locomoção, para ser incrementado em um posterior momento (TCC).

Em um primeiro momento realisou-se pesquisa de detecção de objetos nos artigos científicos do IEEE, pois ainda não tinha sido decidido se o projeto será para cortar grama, ou remover a grama de paralelepípedo. Os artigos que mais chamaram a atenção foram os citados abixo:


Y. Guo and F. Sun, "Efficient visual obstacle avoidance for robotic mower," 2017 2nd International Conference on Control and Robotics Engineering (ICCRE), Bangkok, 2017, pp. 23-28.
doi: 10.1109/ICCRE.2017.7935035
keywords: {collision avoidance;feature extraction;Gabor filters;image classification;image coding;image texture;mobile robots;motion control;robot vision;support vector machines;tree searching;visual obstacle avoidance;robotic mower lawn obstacle avoidance;motion control;Gabor texture classification;drivable region search methods;cameras;real-time image streams;obstacle avoidance rate;complex scenes;ROS;robot operating system;region search;polygon window area;BFS method;breadth-first search method;maximum connected drivable region;grass texture classification task;SVM model;compressed features;robust texture feature extraction;Gabor filters;lawn scenes;Robots;Collision avoidance;Principal component analysis;Cameras;Feature extraction;Support vector machines;Gabor filters;component;Robotic Mower;Obstacle avoidance;Texture Classification;Support Vector Machine;Window Search;Robot Operating System},
URL: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7935035&isnumber=7935023


M. Franzius, M. Dunn, N. Einecke and R. Dirnberger, "Embedded Robust Visual Obstacle Detection on Autonomous Lawn Mowers," 2017 IEEE Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), Honolulu, HI, 2017, pp. 361-369.
doi: 10.1109/CVPRW.2017.50
keywords: {cameras;collision avoidance;image colour analysis;lighting;microcontrollers;mobile robots;object detection;robot vision;service robots;embedded robust visual obstacle detection;autonomous lawn mowers;service robots;floor cleaners;camera-based noncontact obstacle avoidance;low-cost compact module;color cameras;ARM-based processing board;color-based obstacle avoidance;camera control;outdoor lighting conditions;mowing performance;camera-based mower;noncamera-based mower;Cameras;Sun;Robots;Collision avoidance;Image color analysis;Image segmentation;Robustness},
URL: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8014784&isnumber=8014734


Xi Lu, Yu Liu, Huijiang Du and Shixin Xu, "The uncut lawn cognition algorithm based on image analysis," Proceeding of the 11th World Congress on Intelligent Control and Automation, Shenyang, 2014, pp. 5138-5142.
doi: 10.1109/WCICA.2014.7053589
keywords: {edge detection;feature extraction;image capture;image thinning;mobile robots;object recognition;robot vision;service robots;shape recognition;uncut lawn cognition algorithm;image analysis;uncut lawn recognition;robotic mowers;image data capture;edge detection;image binarization;image erosion;freeman chain code;target contour extraction;contour filling;filling area thinning;thinned skeleton pruning;shape features;grass length;grass width;sunny days;overcast days;Algorithm design and analysis;Cognition;Feature extraction;Automation;Robots;Image edge detection;Filling;uncut lawn;target extraction;shape features;robotic movers},
URL: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7053589&isnumber=7052676


A. Schepelmann, R. E. Hudson, F. L. Merat and R. D. Quinn, "Visual segmentation of lawn grass for a mobile robotic lawnmower," 2010 IEEE/RSJ International Conference on Intelligent Robots and Systems, Taipei, 2010, pp. 734-739.
doi: 10.1109/IROS.2010.5650430
keywords: {image segmentation;mobile robots;pattern clustering;robot vision;statistical analysis;visual segmentation;lawn grass;mobile robotic lawn mower;first order statistics;second order statistics;statistical clustering;artificial texture;driveable terrain identification;autonomous lawnmower;Gray-scale;Pixel;Image edge detection;Image color analysis;Robots;Cameras;Image segmentation},
URL: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5650430&isnumber=5648787

Após sugestão dos professores foi realizada pesqueisa nós produtos comerciais para ter noção de como eles fazem o corte/ mobilidade/ sensoriamento. O link abaixo é um projeto de cortador de grama implementado com arduino mega:
https://www.instructables.com/id/Lawnmower-Robot/

O link a seguir é de um produto da empresa slanetrac no qual é utilizado para limpar pavimentação de blocos:
https://www.youtube.com/watch?time_continue=67&v=UnSY1sU3HoU&feature=emb_logo

Com base dessas pesquisas decidiu-se utilizar um raspberry pi devido a possibilidade de incrementar o projeto, utilizar de sensoriamento de câmeras e o sistema de sensor ultrasônico (devido ao preço)

Com relação aos mortores ainda não foi consolidado qual escolher, mas para as rodas (ou lagarta) será um com baixo rpm e auto torque ( devido a não decisão do peso e o cortador não precisa ser rápido) 

