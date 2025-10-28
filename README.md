# Team-02

Task-01

1. First I imported Pillow library for operations on images

2. I uploaded an image and loaded it using Pillow (PIL)

3. Now I provided it with a secret image and converted it to binary form

4. Now I encoded the secret message in only red channel by first clearing the last bit of it and replacing it with the bit of message to be encoded

5. This results in a new updated pixels' list, whose image looks identical to human eye. Now I stored the encoded image

6. During decoding, I extracted red values, collected their last bit, grouped every 8 bits and converted them to characters and then displayed it.
