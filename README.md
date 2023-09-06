#include <stdio.h>
#include <math.h>

int main() {
    double x1 = 3, y1 = 5, x2 = 3, y2 = 5; 

    double length = sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));

    printf("Довжина вектора: %.6lf\n", length);

    return 0;
}

