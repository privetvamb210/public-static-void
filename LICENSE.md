public class MergeSort {
    public static void main(String[] args) {
        int[] array = {5, 2, 8, 3, 1, 7, 6, 4};

        System.out.println("Исходный массив:");
        printArray(array);

        mergeSort(array, 0, array.length - 1);

        System.out.println("Отсортированный массив:");
        printArray(array);
    }
