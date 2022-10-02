import static java.lang.Math.*;
//import static java.lang.Math.sqrt;

public class Test1 {

	public static void main(String[] args) {

		String[] a = { "ker", "juhg", "he", "js", "luo", "he", "guang", "hui" };
		for (String k : a) {
			System.out.print(k);
		}
		System.out.println(a.length);
		double r1 = Math.random();
		int r = (int) (r1 * 100 + 1);
		System.out.println(r1);
		System.out.println(r);
		System.out.println(sqrt(27.0));
		System.out.println(sin(27.0));
	}

}
