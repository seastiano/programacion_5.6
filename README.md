# programacion_5.6
%numeral 5.6
%numeral 5.7 adicionar marcadores triangulares
J=linspace(0,2*pi,20);
YA=sin (J);
YB=cos(J);
YC=sin(J)+cos(J);
plot(J,YA,'>Y')
hold on
plot(J,YB,'>g')
hold on
plot(J,YC,'>r')
xlabel('vector j')
ylabel('magnitud de ya yb yc')
title('numeral 5.6')
grid on 
legend('yA')
