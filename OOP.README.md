# InpsydeTask
// Use wp_nonce*()function implemented in OOP way 
Please create a composer package, which serves the functionality working with WordPress Nonces. That means to have especially wp_nonce_*() function implemented in an object orientated way. You don't have to replace the current functionality, just implement the WordPress Nonces more like OOP. README is mandatory, UnitTests desired. Create a repository on Github for this project, showing us the process.

Any advice:
Codex
Code Style
Object-oriented architecture and implementation
Composer // 

class My_Nonce {
   public function my_nonce_field( $action = -1, $name = "_wpnonce", $referer = true , $echo = true ) {
      return wp_nonce_field( $action, $name, $referer, $echo );
   }
}
