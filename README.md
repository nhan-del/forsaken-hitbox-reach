# forsaken-hitbox-reach
Reach 20 hitbox
public class Forsaken {
    public static void main(String[] args) {
        // Create a hitbox with default size
        Hitbox hitbox = new Hitbox();
        hitbox.setSize(20);
        System.out.println("Hitbox size set to: " + hitbox.getSize());
    }
}

// Simple Hitbox class for demonstration
class Hitbox {
    private int size;

    public Hitbox() {
        this.size = 0;
    }

    public void setSize(int size) {
        this.size = size;
    }

    public int getSize() {
        return size;
    }
}
