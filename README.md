package AssignmentPack;

public class Ses2Assignment2 {

	public static void primeNumber(int num) {
		for (int i = 2; i <= num; i++) {
			int half = i / 2;
			int flag = 0;

			for (int j = 2; j <= half; j++) {
				if (i % j == 0) {
					flag = 1;
					break;
				}
			}
				if (flag == 0)
				System.out.println("Prime no. is " + i);

		}
	}
	public static void main(String[] args) {

		Ses2Assignment2.primeNumber(20);
}
}
