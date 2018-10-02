# VicTrie
Simplest possible Trie tree

my $vic = Vic::Trie->new; 
$vic->add('123');
$vic->add('123456');
$vic->add('123456789');

say Dumper $vic;        

$VAR1 = bless( {
                 'head' => {
                             '1' => {
                                      '2' => {
                                               '3' => {
                                                        '4' => {
                                                                 '5' => {
                                                                          '6' => {
                                                                                   '7' => {
                                                                                            '8' => {
                                                                                                     '9' => {
                                                                                                              '*' => 1
                                                                                                            }
                                                                                                   }
                                                                                          },
                                                                                   '*' => 1
                                                                                 }
                                                                        }
                                                               },
                                                        '*' => 1
                                                      }
                                             }
                                    }
                           }
               }, 'Vic::Trie' );

