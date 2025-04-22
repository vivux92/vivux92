{{in_array ('html',$data->checkbox ??[]) ? 'checked' :''}}


$user->checkbox = (isset($user->checkbox) && $user->checkbox ? explode(',', $user->checkbox) : []);
